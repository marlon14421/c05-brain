---
type: "Malware"
source: MITRE ATT&CK
id: "S0458"
source_url: "https://attack.mitre.org/software/S0458"
created: "2020-05-27"
modified: "2025-04-25"
---
# S0458: Ramsay

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0458  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[Ramsay](https://attack.mitre.org/software/S0458) is an information stealing malware framework designed to collect and exfiltrate sensitive documents, including from air-gapped systems. Researchers have identified overlaps between [Ramsay](https://attack.mitre.org/software/S0458) and the [Darkhotel](https://attack.mitre.org/groups/G0012)-associated Retro malware.(Citation: Eset Ramsay May 2020)(Citation: Antiy CERT Ramsay April 2020)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0458](https://attack.mitre.org/software/S0458)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
