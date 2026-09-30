---
type: "Malware"
source: MITRE ATT&CK
id: "S1153"
source_url: "https://attack.mitre.org/software/S1153"
created: "2024-08-20"
modified: "2024-10-28"
---
# S1153: Cuckoo Stealer

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1153  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

[Cuckoo Stealer](https://attack.mitre.org/software/S1153) is a macOS malware with characteristics of spyware and an infostealer that has been in use since at least 2024. [Cuckoo Stealer](https://attack.mitre.org/software/S1153) is a universal Mach-O binary that can run on Intel or ARM-based Macs and has been spread through trojanized versions of various potentially unwanted programs or PUP's such as converters, cleaners, and uninstallers.(Citation: Kandji Cuckoo April 2024)(Citation: SentinelOne Cuckoo Stealer May 2024)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1153](https://attack.mitre.org/software/S1153)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
