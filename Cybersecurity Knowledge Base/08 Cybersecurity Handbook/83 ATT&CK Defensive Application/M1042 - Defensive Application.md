---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "M1042"
attack_type: "Mitigation"
source: MITRE ATT&CK
---
# M1042: Disable or Remove Feature or Program — Defensive Application

## Source record

- [[01 ATT&CK/M1042 - Disable or Remove Feature or Program|M1042 source record]]
- ATT&CK class: Mitigation
- Platforms: Not specified
- Tactics: Not specified

## Source context

Disable or remove unnecessary and potentially vulnerable software, features, or services to reduce the attack surface and prevent abuse by adversaries. This involves identifying software or features that are no longer needed or that could be exploited and ensuring they are either removed or properly disabled. This mitigation can be implemented through the following measures: Remove Legacy Software: - Use Case: Disable or remove older versions of software that no longer receive updates or security patches (e.g., legacy Java, Adobe Flash). - Implementation: A company removes Flash Player from all employee systems after it has reached its end-of-life date. Disable Unused Features: - Use Case: Turn off unnecessary operating system features like SMBv1, Telnet, or RDP if they are not required. - Implementation: Disable SMBv1 in a Windows environment to mitigate vulnerabilities like EternalBlue. Control Applications Installed by Users: - Use Case: Prevent users from installing unauthorized software via group policies or other management tools. - Implementation: Block user installations of unauthorized file-sharing applications (e.g., BitTorrent clients) in an enterprise environment. Remove Unnecessary Services: - Use Case: Identify and disable unnecessary default services running on endpoints, servers, or network devices. - Implementation: Disable unused administrative shares (e.g., C$, ADMIN$) on workstations. Restrict Add-ons and Plugins: - Use Case: Remove or disable browser plugins and add-ons that are not needed for business purposes. - Implementation: Disable Java and ActiveX plugins in web browsers to prevent drive-by attacks.

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
