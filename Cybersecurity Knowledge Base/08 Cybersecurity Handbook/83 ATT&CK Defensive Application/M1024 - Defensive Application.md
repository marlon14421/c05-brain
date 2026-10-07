---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "M1024"
attack_type: "Mitigation"
source: MITRE ATT&CK
---
# M1024: Restrict Registry Permissions — Defensive Application

## Source record

- [[01 ATT&CK/M1024 - Restrict Registry Permissions|M1024 source record]]
- ATT&CK class: Mitigation
- Platforms: Not specified
- Tactics: Not specified

## Source context

Restricting registry permissions involves configuring access control settings for sensitive registry keys and hives to ensure that only authorized users or processes can make modifications. By limiting access, organizations can prevent unauthorized changes that adversaries might use for persistence, privilege escalation, or defense evasion. This mitigation can be implemented through the following measures: Review and Adjust Permissions on Critical Keys - Regularly review permissions on keys such as `Run`, `RunOnce`, and `Services` to ensure only authorized users have write access. - Use tools like `icacls` or `PowerShell` to automate permission adjustments. Enable Registry Auditing - Enable auditing on sensitive keys to log access attempts. - Use Event Viewer or SIEM solutions to analyze logs and detect suspicious activity. - Example Audit Policy: `auditpol /set /subcategory:"Registry" /success:enable /failure:enable` Protect Credential-Related Hives - Limit access to hives like `SAM`,`SECURITY`, and `SYSTEM` to prevent credential dumping or other unauthorized access. - Use LSA Protection to add an additional security layer for credential storage. Restrict Registry Editor Usage - Use Group Policy to restrict access to regedit.exe for non-administrative users. - Block execution of registry editing tools on endpoints where they are unnecessary. Deploy Baseline Configuration Tools - Use tools like Microsoft Security Compliance Toolkit or CIS Benchmarks to apply and maintain secure registry configurations. *Tools for Implementation* Registry Permission Tools: - Registry Editor (regedit): Built-in tool to manage registry permissions. - PowerShell: Automate permissions and manage keys. `Set-ItemProperty -Path "HKLM:\Software\Microsoft\Windows\CurrentVersion\Run" -Name "KeyName" -Value "Value"` - icacls: Command-line tool to modify ACLs. Monitoring Tools: - Sysmon: Monitor and log registry events. - Event Viewer: View registry access logs. Policy Management Tools: - Group Policy Management Console (GPMC): Enforce registry permissions via GPOs. - Microsoft Endpoint Manager: Deploy configuration baselines for registry permissions.

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
