---
type: "Malware"
source: MITRE ATT&CK
id: "S1232"
source_url: "https://attack.mitre.org/software/S1232"
created: "2025-09-12"
modified: "2025-10-21"
---
# S1232: SplatDropper

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1232  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[SplatDropper](https://attack.mitre.org/software/S1232) is a loader that utilizes native windows API to deliver its payload to the victim environment. [SplatDropper](https://attack.mitre.org/software/S1232) has been delivered through RAR archives and used legitimate executable for DLL side-loading. [SplatDropper](https://attack.mitre.org/software/S1232) is known to be leveraged by [Mustang Panda](https://attack.mitre.org/groups/G0129) and was first observed utilized in 2025.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1232](https://attack.mitre.org/software/S1232)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
