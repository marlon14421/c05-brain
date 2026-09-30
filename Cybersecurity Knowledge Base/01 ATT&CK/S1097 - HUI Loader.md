---
type: "Malware"
source: MITRE ATT&CK
id: "S1097"
source_url: "https://attack.mitre.org/software/S1097"
created: "2023-12-22"
modified: "2024-01-02"
---
# S1097: HUI Loader

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1097  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[HUI Loader](https://attack.mitre.org/software/S1097) is a custom DLL loader that has been used since at least 2015 by China-based threat groups including [Cinnamon Tempest](https://attack.mitre.org/groups/G1021) and [menuPass](https://attack.mitre.org/groups/G0045) to deploy malware on compromised hosts. [HUI Loader](https://attack.mitre.org/software/S1097) has been observed in campaigns loading [SodaMaster](https://attack.mitre.org/software/S0627), [PlugX](https://attack.mitre.org/software/S0013), [Cobalt Strike](https://attack.mitre.org/software/S0154), [Komplex](https://attack.mitre.org/software/S0162), and several strains of ransomware.(Citation: SecureWorks BRONZE STARLIGHT Ransomware Operations June 2022)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1097](https://attack.mitre.org/software/S1097)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
