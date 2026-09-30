---
type: "Malware"
source: MITRE ATT&CK
id: "S0648"
source_url: "https://attack.mitre.org/software/S0648"
created: "2021-09-22"
modified: "2025-04-25"
---
# S0648: JSS Loader

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0648  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[JSS Loader](https://attack.mitre.org/software/S0648) is Remote Access Trojan (RAT) with .NET and C++ variants that has been used by [FIN7](https://attack.mitre.org/groups/G0046) since at least 2020.(Citation: eSentire FIN7 July 2021)(Citation: CrowdStrike Carbon Spider August 2021)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0648](https://attack.mitre.org/software/S0648)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
