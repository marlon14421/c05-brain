---
type: "Malware"
source: MITRE ATT&CK
id: "S9011"
source_url: "https://attack.mitre.org/software/S9011"
created: "2026-04-13"
modified: "2026-04-23"
---
# S9011: BRUSHFIRE

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S9011  
**Platforms:** Linux, Network Devices  
**Tactics:** Not specified

## Source description

[BRUSHFIRE](https://attack.mitre.org/software/S9011) is a passive backdoor written in C that executes in-memory within an existing process. First reported in March 2025, [BRUSHFIRE](https://attack.mitre.org/software/S9011) has been observed in activity attributed to People's Republic of China (PRC) state-affiliated threat actors, including UNC5221 and SYLVANITE.(Citation: Dragos SYLVANITE MuddyWater Electrum March 2026)(Citation: Google UNC5221 Ivanti April 2025)(Citation: Picus Security UNC5221 Ivanti May 2025)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S9011](https://attack.mitre.org/software/S9011)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
