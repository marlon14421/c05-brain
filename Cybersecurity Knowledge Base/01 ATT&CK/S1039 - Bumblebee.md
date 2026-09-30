---
type: "Malware"
source: MITRE ATT&CK
id: "S1039"
source_url: "https://attack.mitre.org/software/S1039"
created: "2022-08-19"
modified: "2024-09-17"
---
# S1039: Bumblebee

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1039  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[Bumblebee](https://attack.mitre.org/software/S1039) is a custom loader written in C++ that has been used by multiple threat actors, including possible initial access brokers, to download and execute additional payloads since at least March 2022. [Bumblebee](https://attack.mitre.org/software/S1039) has been linked to ransomware operations including [Conti](https://attack.mitre.org/software/S0575), Quantum, and Mountlocker and derived its name from the appearance of "bumblebee" in the user-agent.(Citation: Google EXOTIC LILY March 2022)(Citation: Proofpoint Bumblebee April 2022)(Citation: Symantec Bumblebee June 2022)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1039](https://attack.mitre.org/software/S1039)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
