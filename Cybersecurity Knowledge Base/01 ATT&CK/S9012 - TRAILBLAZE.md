---
type: "Malware"
source: MITRE ATT&CK
id: "S9012"
source_url: "https://attack.mitre.org/software/S9012"
created: "2026-04-14"
modified: "2026-04-23"
---
# S9012: TRAILBLAZE

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S9012  
**Platforms:** Linux, Network Devices  
**Tactics:** Not specified

## Source description

[TRAILBLAZE](https://attack.mitre.org/software/S9012) is an in-memory dropper used to deploy the passive backdoor [BRUSHFIRE](https://attack.mitre.org/software/S9011). First reported in March 2025, TRAILBLAZE has been observed in operations attributed to People's Republic of China (PRC) state-sponsored affiliated actors, including UNC5221 and SYLVANITE. (Citation: Dragos SYLVANITE MuddyWater Electrum March 2026)(Citation: Google UNC5221 Ivanti April 2025)(Citation: Picus Security UNC5221 Ivanti May 2025)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S9012](https://attack.mitre.org/software/S9012)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
