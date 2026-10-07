---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "M1038"
attack_type: "Mitigation"
source: MITRE ATT&CK
---
# M1038: Execution Prevention — Defensive Application

## Source record

- [[01 ATT&CK/M1038 - Execution Prevention|M1038 source record]]
- ATT&CK class: Mitigation
- Platforms: Not specified
- Tactics: Not specified

## Source context

Prevent the execution of unauthorized or malicious code on systems by implementing application control, script blocking, and other execution prevention mechanisms. This ensures that only trusted and authorized code is executed, reducing the risk of malware and unauthorized actions. This mitigation can be implemented through the following measures: Application Control: - Use Case: Use tools like AppLocker or Windows Defender Application Control (WDAC) to create whitelists of authorized applications and block unauthorized ones. On Linux, use tools like SELinux or AppArmor to define mandatory access control policies for application execution. - Implementation: Allow only digitally signed or pre-approved applications to execute on servers and endpoints. (e.g., `New-AppLockerPolicy -PolicyType Enforced -FilePath "C:\Policies\AppLocker.xml"`) Script Blocking: - Use Case: Use script control mechanisms to block unauthorized execution of scripts, such as PowerShell or JavaScript. Web Browsers: Use browser extensions or settings to block JavaScript execution from untrusted sources. - Implementation: Configure PowerShell to enforce Constrained Language Mode for non-administrator users. (e.g., `Set-ExecutionPolicy AllSigned`) Executable Blocking: - Use Case: Prevent execution of binaries from suspicious locations, such as `%TEMP%` or `%APPDATA%` directories. - Implementation: Block execution of `.exe`, `.bat`, or `.ps1` files from user-writable directories. Dynamic Analysis Prevention: - Use Case: Use behavior-based execution prevention tools to identify and block malicious activity in real time. - Implemenation: Employ EDR solutions that analyze runtime behavior and block suspicious code execution.

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
