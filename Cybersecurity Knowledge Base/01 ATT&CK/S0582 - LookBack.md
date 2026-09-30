---
type: "Malware"
source: MITRE ATT&CK
id: "S0582"
source_url: "https://attack.mitre.org/software/S0582"
created: "2021-03-01"
modified: "2025-04-25"
---
# S0582: LookBack

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0582  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[LookBack](https://attack.mitre.org/software/S0582) is a remote access trojan written in C++ that was used against at least three US utility companies in July 2019. The TALONITE activity group has been observed using [LookBack](https://attack.mitre.org/software/S0582).(Citation: Proofpoint LookBack Malware Aug 2019)(Citation: Dragos TALONITE)(Citation: Dragos Threat Report 2020)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0582](https://attack.mitre.org/software/S0582)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
