---
type: "Threat Group"
source: MITRE ATT&CK
id: "G1050"
source_url: "https://attack.mitre.org/groups/G1050"
created: "2025-09-29"
modified: "2026-07-31"
---
# G1050: Water Galura

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Threat Group  
**ATT&CK ID:** G1050  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

[Water Galura](https://attack.mitre.org/groups/G1050) are the operators of the [Qilin](https://attack.mitre.org/software/S1242) Ransomware-as-a-Service (RaaS) who handle payload generation, ransom negotiations, and the publication of stolen data for [Qilin](https://attack.mitre.org/software/S1242) affilates recruited on Russian cybercrime forums. [Water Galura](https://attack.mitre.org/groups/G1050) have been active since at least 2022 and use a double extortion model where they demand payment for providing decryption keys and for refraining from publishing the stolen data to their leak site.(Citation: BushidoToken Qilin RaaS JUN 2024)(Citation: Sophos Qilin MSP APR 2025)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: G1050](https://attack.mitre.org/groups/G1050)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
