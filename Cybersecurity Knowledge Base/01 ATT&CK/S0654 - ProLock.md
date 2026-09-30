---
type: "Malware"
source: MITRE ATT&CK
id: "S0654"
source_url: "https://attack.mitre.org/software/S0654"
created: "2021-09-30"
modified: "2024-11-17"
---
# S0654: ProLock

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0654  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[ProLock](https://attack.mitre.org/software/S0654) is a ransomware strain that has been used in Big Game Hunting (BGH) operations since at least 2020, often obtaining initial access with [QakBot](https://attack.mitre.org/software/S0650). [ProLock](https://attack.mitre.org/software/S0654) is the successor to PwndLocker ransomware which was found to contain a bug allowing decryption without ransom payment in 2019.(Citation: Group IB Ransomware September 2020)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0654](https://attack.mitre.org/software/S0654)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
