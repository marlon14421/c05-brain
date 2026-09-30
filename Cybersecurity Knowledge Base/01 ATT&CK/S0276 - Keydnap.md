---
type: "Malware"
source: MITRE ATT&CK
id: "S0276"
source_url: "https://attack.mitre.org/software/S0276"
created: "2018-10-17"
modified: "2024-01-10"
---
# S0276: Keydnap

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0276  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

This piece of malware steals the content of the user's keychain while maintaining a permanent backdoor (Citation: OSX Keydnap malware).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0276](https://attack.mitre.org/software/S0276)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
