---
type: "Malware"
source: MITRE ATT&CK
id: "S0658"
source_url: "https://attack.mitre.org/software/S0658"
created: "2021-10-05"
modified: "2025-04-04"
---
# S0658: XCSSET

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0658  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

[XCSSET](https://attack.mitre.org/software/S0658) is a modular macOS malware family delivered through infected Xcode projects and executed when the project is compiled. Active since August 2020, it has been observed installing backdoors, spoofed browsers, collecting data, and encrypting user files. It is composed of SHC-compiled shell scripts and run-only AppleScripts, often hiding in apps that mimic system tools (such as Xcode, Mail, or Notes) or use familiar icons (like Launchpad) to avoid detection.(Citation: trendmicro xcsset xcode project 2020)(Citation: April 2021 TrendMicro XCSSET)(Citation: Microsoft March 2025 XCSSET)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0658](https://attack.mitre.org/software/S0658)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
