---
type: "Malware"
source: MITRE ATT&CK
id: "S1236"
source_url: "https://attack.mitre.org/software/S1236"
created: "2025-09-12"
modified: "2025-10-21"
---
# S1236: CLAIMLOADER

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1236  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[CLAIMLOADER](https://attack.mitre.org/software/S1236) is a malware variant that frequently accompanies legitimate executables that are used for DLL side-loading known to be leveraged by [Mustang Panda](https://attack.mitre.org/groups/G0129) and was first observed utilized in 2021.(Citation: IBM MUSTANG PANDA PUBLOAD CLAIMLOADER JUNE 2025)(Citation: 2025_IBM_PUBLOAD_TONESHELL_HIUPAN_CLAIMLOADER_MUSTANG PANDA)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1236](https://attack.mitre.org/software/S1236)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
