---
type: "Malware"
source: MITRE ATT&CK
id: "S1191"
source_url: "https://attack.mitre.org/software/S1191"
created: "2025-01-08"
modified: "2025-03-11"
---
# S1191: Megazord

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1191  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[Megazord](https://attack.mitre.org/software/S1191) is a Rust-based variant of [Akira](https://attack.mitre.org/software/S1129) ransomware that has been in use since at least August 2023 to target Windows environments. [Megazord](https://attack.mitre.org/software/S1191) has been attributed to the [Akira](https://attack.mitre.org/groups/G1024) group based on overlapping infrastructure though is possibly not exclusive to the group.(Citation: CISA Akira Ransomware APR 2024)(Citation: Cisco Akira Ransomware OCT 2024)(Citation: Palo Alto Howling Scorpius DEC 2024)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1191](https://attack.mitre.org/software/S1191)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
