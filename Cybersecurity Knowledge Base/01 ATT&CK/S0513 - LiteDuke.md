---
type: "Malware"
source: MITRE ATT&CK
id: "S0513"
source_url: "https://attack.mitre.org/software/S0513"
created: "2020-09-24"
modified: "2025-04-25"
---
# S0513: LiteDuke

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0513  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[LiteDuke](https://attack.mitre.org/software/S0513) is a third stage backdoor that was used by [APT29](https://attack.mitre.org/groups/G0016), primarily in 2014-2015. [LiteDuke](https://attack.mitre.org/software/S0513) used the same dropper as [PolyglotDuke](https://attack.mitre.org/software/S0518), and was found on machines also compromised by [MiniDuke](https://attack.mitre.org/software/S0051).(Citation: ESET Dukes October 2019)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0513](https://attack.mitre.org/software/S0513)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
