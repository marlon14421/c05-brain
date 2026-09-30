---
type: "Malware"
source: MITRE ATT&CK
id: "S0016"
source_url: "https://attack.mitre.org/software/S0016"
created: "2017-05-31"
modified: "2024-04-24"
---
# S0016: P2P ZeuS

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0016  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[P2P ZeuS](https://attack.mitre.org/software/S0016) is a closed-source fork of the leaked version of the ZeuS botnet. It presents improvements over the leaked version, including a peer-to-peer architecture. (Citation: Dell P2P ZeuS)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0016](https://attack.mitre.org/software/S0016)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
