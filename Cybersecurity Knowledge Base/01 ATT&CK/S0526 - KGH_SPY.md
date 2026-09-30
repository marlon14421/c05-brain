---
type: "Malware"
source: MITRE ATT&CK
id: "S0526"
source_url: "https://attack.mitre.org/software/S0526"
created: "2020-11-06"
modified: "2024-04-11"
---
# S0526: KGH_SPY

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0526  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[KGH_SPY](https://attack.mitre.org/software/S0526) is a modular suite of tools used by [Kimsuky](https://attack.mitre.org/groups/G0094) for reconnaissance, information stealing, and backdoor capabilities. [KGH_SPY](https://attack.mitre.org/software/S0526) derived its name from PDB paths and internal names found in samples containing "KGH".(Citation: Cybereason Kimsuky November 2020)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0526](https://attack.mitre.org/software/S0526)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
