---
type: "Malware"
source: MITRE ATT&CK
id: "S0516"
source_url: "https://attack.mitre.org/software/S0516"
created: "2020-09-29"
modified: "2025-10-22"
---
# S0516: SoreFang

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0516  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[SoreFang](https://attack.mitre.org/software/S0516) is first stage downloader used by [APT29](https://attack.mitre.org/groups/G0016) for exfiltration and to load other malware.(Citation: NCSC APT29 July 2020)(Citation: CISA SoreFang July 2016)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0516](https://attack.mitre.org/software/S0516)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
