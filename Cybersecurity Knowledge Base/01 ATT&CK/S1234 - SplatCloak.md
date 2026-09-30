---
type: "Malware"
source: MITRE ATT&CK
id: "S1234"
source_url: "https://attack.mitre.org/software/S1234"
created: "2025-09-12"
modified: "2025-10-21"
---
# S1234: SplatCloak

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1234  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[SplatCloak](https://attack.mitre.org/software/S1234) is a malware that disables EDR-related routines used by Windows Defender and Kaspersky to aid in evading detection. [SplatCloak](https://attack.mitre.org/software/S1234) has been deployed by [SplatDropper](https://attack.mitre.org/software/S1232) and is known to be leveraged by [Mustang Panda](https://attack.mitre.org/groups/G0129) since 2025.(Citation: Zscaler PAKLOG CorkLog SplatCloak Splatdropper April 2025)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1234](https://attack.mitre.org/software/S1234)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
