---
type: "Malware"
source: MITRE ATT&CK
id: "S0453"
source_url: "https://attack.mitre.org/software/S0453"
created: "2020-05-21"
modified: "2025-04-25"
---
# S0453: Pony

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0453  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[Pony](https://attack.mitre.org/software/S0453) is a credential stealing malware, though has also been used among adversaries for its downloader capabilities. The source code for Pony Loader 1.0 and 2.0 were leaked online, leading to their use by various threat actors.(Citation: Malwarebytes Pony April 2016)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0453](https://attack.mitre.org/software/S0453)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
