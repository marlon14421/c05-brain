---
type: "Malware"
source: MITRE ATT&CK
id: "S0537"
source_url: "https://attack.mitre.org/software/S0537"
created: "2020-12-02"
modified: "2026-01-20"
---
# S0537: HyperStack

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0537  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[HyperStack](https://attack.mitre.org/software/S0537) is a RPC-based backdoor used by [Turla](https://attack.mitre.org/groups/G0010) since at least 2018. [HyperStack](https://attack.mitre.org/software/S0537) has similarities to other backdoors used by [Turla](https://attack.mitre.org/groups/G0010) including [Carbon](https://attack.mitre.org/software/S0335).(Citation: Accenture HyperStack October 2020)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0537](https://attack.mitre.org/software/S0537)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
