---
type: "Malware"
source: MITRE ATT&CK
id: "S0578"
source_url: "https://attack.mitre.org/software/S0578"
created: "2021-02-18"
modified: "2024-04-10"
---
# S0578: SUPERNOVA

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0578  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[SUPERNOVA](https://attack.mitre.org/software/S0578) is an in-memory web shell written in .NET C#. It was discovered in November 2020 during the investigation of [APT29](https://attack.mitre.org/groups/G0016)'s SolarWinds cyber operation but determined to be unrelated. Subsequent analysis suggests [SUPERNOVA](https://attack.mitre.org/software/S0578) may have been used by the China-based threat group SPIRAL.(Citation: Guidepoint SUPERNOVA Dec 2020)(Citation: Unit42 SUPERNOVA Dec 2020)(Citation: SolarWinds Advisory Dec 2020)(Citation: CISA Supernova Jan 2021)(Citation: Microsoft Analyzing Solorigate Dec 2020)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0578](https://attack.mitre.org/software/S0578)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
