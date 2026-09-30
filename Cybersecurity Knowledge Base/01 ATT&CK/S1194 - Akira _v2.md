---
type: "Malware"
source: MITRE ATT&CK
id: "S1194"
source_url: "https://attack.mitre.org/software/S1194"
created: "2025-01-09"
modified: "2025-03-11"
---
# S1194: Akira _v2

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1194  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

[Akira _v2](https://attack.mitre.org/software/S1194) is a Rust-based variant of [Akira](https://attack.mitre.org/software/S1129) ransomware that has been in use since at least 2024. [Akira _v2](https://attack.mitre.org/software/S1194) is designed to target VMware ESXi servers and includes a new command-line argument set and other expanded capabilities.(Citation: CISA Akira Ransomware APR 2024)(Citation: Cisco Akira Ransomware OCT 2024)(Citation: Palo Alto Howling Scorpius DEC 2024)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1194](https://attack.mitre.org/software/S1194)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
