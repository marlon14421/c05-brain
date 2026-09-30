---
type: "Malware"
source: MITRE ATT&CK
id: "S1156"
source_url: "https://attack.mitre.org/software/S1156"
created: "2024-09-04"
modified: "2024-09-06"
---
# S1156: Manjusaka

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1156  
**Platforms:** Linux, Windows  
**Tactics:** Not specified

## Source description

[Manjusaka](https://attack.mitre.org/software/S1156) is a Chinese-language intrusion framework, similar to [Sliver](https://attack.mitre.org/software/S0633) and [Cobalt Strike](https://attack.mitre.org/software/S0154), with an ELF binary written in GoLang as the controller for Windows and Linux implants written in Rust. First identified in 2022, [Manjusaka](https://attack.mitre.org/software/S1156) consists of multiple components, only one of which (a command and control module) is freely available.(Citation: Talos Manjusaka 2022)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1156](https://attack.mitre.org/software/S1156)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
