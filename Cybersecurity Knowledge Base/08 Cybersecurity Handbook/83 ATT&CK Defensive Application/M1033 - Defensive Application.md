---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "M1033"
attack_type: "Mitigation"
source: MITRE ATT&CK
---
# M1033: Limit Software Installation — Defensive Application

## Source record

- [[01 ATT&CK/M1033 - Limit Software Installation|M1033 source record]]
- ATT&CK class: Mitigation
- Platforms: Not specified
- Tactics: Not specified

## Source context

Prevent users or groups from installing unauthorized or unapproved software to reduce the risk of introducing malicious or vulnerable applications. This can be achieved through allowlists, software restriction policies, endpoint management tools, and least privilege access principles. This mitigation can be implemented through the following measures: Application Whitelisting - Implement Microsoft AppLocker or Windows Defender Application Control (WDAC) to create and enforce allowlists for approved software. - Whitelist applications based on file hash, path, or digital signatures. Restrict User Permissions - Remove local administrator rights for all non-IT users. - Use Role-Based Access Control (RBAC) to restrict installation permissions to privileged accounts only. Software Restriction Policies (SRP) - Use GPO to configure SRP to deny execution of binaries from directories such as `%AppData%`, `%Temp%`, and external drives. - Restrict specific file types (`.exe`, `.bat`, `.msi`, `.js`, `.vbs`) to trusted directories only. Endpoint Management Solutions - Deploy tools like Microsoft Intune, SCCM, or Jamf for centralized software management. - Maintain a list of approved software, versions, and updates across the enterprise. Monitor Software Installation Events - Enable logging of software installation events and monitor Windows Event ID 4688 and Event ID 11707 for software installs. - Use SIEM or EDR tools to alert on attempts to install unapproved software. Implement Software Inventory Management - Use tools like OSQuery or Wazuh to scan for unauthorized software on endpoints and servers. - Conduct regular audits to detect and remove unapproved software. *Tools for Implementation* Application Whitelisting: - Microsoft AppLocker - Windows Defender Application Control (WDAC) Endpoint Management: - Microsoft Intune - SCCM (System Center Configuration Manager) - Jamf Pro (macOS) - Puppet or Ansible for automation Software Restriction Policies: - Group Policy Object (GPO) - Microsoft Software Restriction Policies (SRP) Monitoring and Logging: - Splunk - OSQuery - Wazuh (open-source SIEM and XDR) - EDRs Inventory Management and Auditing: - OSQuery - Wazuh

## Defensive focus

Assess the control as an implementable safeguard with a defined owner, target population, configuration, exception path, and evidence of operation.

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Review checklist

- Which assets and versions support this control, and where are exceptions required?
- Does the control reduce the relevant exposure without disabling a legitimate business function?
- How is coverage measured and configuration drift detected?
- What compensating control applies where the primary safeguard is unavailable?
- What test demonstrates continued effectiveness after updates?

## Safe validation

Pilot configuration changes in a representative test group, obtain owner approval, and preserve a tested rollback plan. Define written scope, test window, accounts, data boundaries, and stop conditions in advance. Preserve only the evidence required to verify the control and protect it from unauthorized access.

## Evidence and response

Record the source and version, environment, time range, expected behavior, observations, alternative explanations, and telemetry gaps. A catalog mapping is a lead for analysis, not an incident finding. Escalate and contain only under approved response procedures; verify remediation with a measurable retest.

## Further reading

- [MITRE ATT&CK](https://attack.mitre.org/)
- [[../../04 Defensive Playbooks/Defensive Playbooks|Defensive Playbooks]]
- [[../../06 Sources/Source Register|Source Register and dataset caveats]]
