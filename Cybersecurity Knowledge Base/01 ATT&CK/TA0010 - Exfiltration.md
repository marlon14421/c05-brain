---
type: "Tactic"
source: MITRE ATT&CK
id: "TA0010"
source_url: "https://attack.mitre.org/tactics/TA0010"
created: "2018-10-17"
modified: "2025-04-25"
---
# TA0010: Exfiltration

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Tactic  
**ATT&CK ID:** TA0010  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

The adversary is trying to steal data. Exfiltration consists of techniques that adversaries may use to steal data from your network. Once they’ve collected data, adversaries often package it to avoid detection while removing it. This can include compression and encryption. Techniques for getting data out of a target network typically include transferring it over their command and control channel or an alternate channel and may also include putting size limits on the transmission.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: TA0010](https://attack.mitre.org/tactics/TA0010)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
