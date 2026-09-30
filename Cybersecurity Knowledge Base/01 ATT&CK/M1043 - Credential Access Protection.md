---
type: "Mitigation"
source: MITRE ATT&CK
id: "M1043"
source_url: "https://attack.mitre.org/mitigations/M1043"
created: "2019-06-11"
modified: "2024-12-10"
---
# M1043: Credential Access Protection

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Mitigation  
**ATT&CK ID:** M1043  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

Credential Access Protection focuses on implementing measures to prevent adversaries from obtaining credentials, such as passwords, hashes, tokens, or keys, that could be used for unauthorized access. This involves restricting access to credential storage mechanisms, hardening configurations to block credential dumping methods, and using monitoring tools to detect suspicious credential-related activity. This mitigation can be implemented through the following measures: Restrict Access to Credential Storage: - Use Case: Prevent adversaries from accessing the SAM (Security Account Manager) database on Windows systems. - Implementation: Enforce least privilege principles and restrict administrative access to credential stores such as `C:\Windows\System32\config\SAM`. Use Credential Guard: - Use Case: Isolate LSASS (Local Security Authority Subsystem Service) memory to prevent credential dumping. - Implementation: Enable Windows Defender Credential Guard on enterprise endpoints to isolate secrets and protect them from unauthorized access. Monitor for Credential Dumping Tools: - Use Case: Detect and block known tools like Mimikatz or Windows Credential Editor. - Implementation: Flag suspicious process behavior related to credential dumping. Disable Cached Credentials: - Use Case: Prevent adversaries from exploiting cached credentials on endpoints. - Implementation: Configure group policy to reduce or eliminate the use of cached credentials (e.g., set Interactive logon: Number of previous logons to cache to 0). Enable Secure Boot and Memory Protections: - Use Case: Prevent memory-based attacks used to extract credentials. - Implementation: Configure Secure Boot and enforce hardware-based security features like DEP (Data Execution Prevention) and ASLR (Address Space Layout Randomization).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: M1043](https://attack.mitre.org/mitigations/M1043)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
