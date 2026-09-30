---
type: "Malware"
source: MITRE ATT&CK
id: "S9036"
source_url: "https://attack.mitre.org/software/S9036"
created: "2026-04-21"
modified: "2026-04-23"
---
# S9036: LP-Notes

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S9036  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[LP-Notes](https://attack.mitre.org/software/S9036) is a C/C++ Windows credential stealer used by [MuddyWater](https://attack.mitre.org/groups/G0069). [LP-Notes](https://attack.mitre.org/software/S9036) was named after the `lp-notes.txt` file that is used to store stolen credentials.(Citation: ESET_MuddyWater_Dec2025)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S9036](https://attack.mitre.org/software/S9036)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
