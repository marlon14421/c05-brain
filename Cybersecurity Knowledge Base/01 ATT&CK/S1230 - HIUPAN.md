---
type: "Malware"
source: MITRE ATT&CK
id: "S1230"
source_url: "https://attack.mitre.org/software/S1230"
created: "2025-08-06"
modified: "2025-10-21"
---
# S1230: HIUPAN

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1230  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[HIUPAN](https://attack.mitre.org/software/S1230) (aka U2DiskWatch) is a is a worm that propagates through removable drives known to be leveraged by [Mustang Panda](https://attack.mitre.org/groups/G0129) and was first observed utilized in 2024. (Citation: 2025_IBM_PUBLOAD_TONESHELL_HIUPAN_CLAIMLOADER_MUSTANG PANDA)(Citation: Trend Micro MUSTANG PANDA PUBLOAD HIUPAN SEPTEMBER 2024)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1230](https://attack.mitre.org/software/S1230)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
