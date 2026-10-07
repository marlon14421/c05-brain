---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "M1050"
attack_type: "Mitigation"
source: MITRE ATT&CK
---
# M1050: Exploit Protection — Defensive Application

## Source record

- [[01 ATT&CK/M1050 - Exploit Protection|M1050 source record]]
- ATT&CK class: Mitigation
- Platforms: Not specified
- Tactics: Not specified

## Source context

Deploy capabilities that detect, block, and mitigate conditions indicative of software exploits. These capabilities aim to prevent exploitation by addressing vulnerabilities, monitoring anomalous behaviors, and applying exploit-mitigation techniques to harden systems and software. Operating System Exploit Protections: - Use Case: Enable built-in exploit protection features provided by modern operating systems, such as Microsoft's Exploit Protection, which includes techniques like Data Execution Prevention (DEP), Address Space Layout Randomization (ASLR), and Control Flow Guard (CFG). - Implementation: Enforce DEP for all programs and enable ASLR to randomize memory addresses used by system and application processes. Windows: Configure Exploit Protection through the Windows Security app or deploy settings via Group Policy. `ExploitProtectionExportSettings.exe -path "exploit_settings.xml"` Linux: Use Kernel-level hardening features like SELinux, AppArmor, or GRSEC to enforce memory protections and prevent exploits. Third-Party Endpoint Security: - Use Case: Use endpoint protection tools with built-in exploit protection, such as enhanced memory protection, behavior monitoring, and real-time exploit detection. - Implementation: Deploy tools to detect and block exploitation attempts targeting unpatched software. Virtual Patching: - Use Case: Use tools to implement virtual patches that mitigate vulnerabilities in applications or operating systems until official patches are applied. - Implementation: Use Intrusion Prevention System (IPS) to block exploitation attempts on known vulnerabilities in outdated applications. Hardening Application Configurations: - Use Case: Disable risky application features that can be exploited, such as macros in Microsoft Office or JScript in Internet Explorer. - Implementation: Configure Microsoft Office Group Policies to disable execution of macros in downloaded files.

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
