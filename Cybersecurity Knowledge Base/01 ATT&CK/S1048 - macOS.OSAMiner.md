---
type: "Malware"
source: MITRE ATT&CK
id: "S1048"
source_url: "https://attack.mitre.org/software/S1048"
created: "2022-10-04"
modified: "2025-10-22"
---
# S1048: macOS.OSAMiner

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1048  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

[macOS.OSAMiner](https://attack.mitre.org/software/S1048) is a Monero mining trojan that was first observed in 2018; security researchers assessed [macOS.OSAMiner](https://attack.mitre.org/software/S1048) may have been circulating since at least 2015. [macOS.OSAMiner](https://attack.mitre.org/software/S1048) is known for embedding one run-only AppleScript into another, which helped the malware evade full analysis for five years due to a lack of Apple event (AEVT) analysis tools.(Citation: SentinelLabs reversing run-only applescripts 2021)(Citation: VMRay OSAMiner dynamic analysis 2021)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1048](https://attack.mitre.org/software/S1048)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
