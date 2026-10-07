---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "M1043"
attack_type: "Mitigation"
source: MITRE ATT&CK
---
# M1043: Credential Access Protection — Defensive Application

## Source record

- [[01 ATT&CK/M1043 - Credential Access Protection|M1043 source record]]
- ATT&CK class: Mitigation
- Platforms: Not specified
- Tactics: Not specified

## Source context

Credential Access Protection focuses on implementing measures to prevent adversaries from obtaining credentials, such as passwords, hashes, tokens, or keys, that could be used for unauthorized access. This involves restricting access to credential storage mechanisms, hardening configurations to block credential dumping methods, and using monitoring tools to detect suspicious credential-related activity. This mitigation can be implemented through the following measures: Restrict Access to Credential Storage: - Use Case: Prevent adversaries from accessing the SAM (Security Account Manager) database on Windows systems. - Implementation: Enforce least privilege principles and restrict administrative access to credential stores such as `C:\Windows\System32\config\SAM`. Use Credential Guard: - Use Case: Isolate LSASS (Local Security Authority Subsystem Service) memory to prevent credential dumping. - Implementation: Enable Windows Defender Credential Guard on enterprise endpoints to isolate secrets and protect them from unauthorized access. Monitor for Credential Dumping Tools: - Use Case: Detect and block known tools like Mimikatz or Windows Credential Editor. - Implementation: Flag suspicious process behavior related to credential dumping. Disable Cached Credentials: - Use Case: Prevent adversaries from exploiting cached credentials on endpoints. - Implementation: Configure group policy to reduce or eliminate the use of cached credentials (e.g., set Interactive logon: Number of previous logons to cache to 0). Enable Secure Boot and Memory Protections: - Use Case: Prevent memory-based attacks used to extract credentials. - Implementation: Configure Secure Boot and enforce hardware-based security features like DEP (Data Execution Prevention) and ASLR (Address Space Layout Randomization).

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
