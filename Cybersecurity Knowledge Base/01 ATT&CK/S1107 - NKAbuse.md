---
type: "Malware"
source: MITRE ATT&CK
id: "S1107"
source_url: "https://attack.mitre.org/software/S1107"
created: "2024-02-08"
modified: "2024-04-13"
---
# S1107: NKAbuse

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1107  
**Platforms:** Linux, macOS, Windows  
**Tactics:** Not specified

## Source description

[NKAbuse](https://attack.mitre.org/software/S1107) is a Go-based, multi-platform malware abusing NKN (New Kind of Network) technology for data exchange between peers, functioning as a potent implant, and equipped with both flooder and backdoor capabilities.(Citation: NKAbuse BC)(Citation: NKAbuse SL)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1107](https://attack.mitre.org/software/S1107)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
