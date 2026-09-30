---
type: "Malware"
source: MITRE ATT&CK
id: "S9014"
source_url: "https://attack.mitre.org/software/S9014"
created: "2026-04-16"
modified: "2026-05-12"
---
# S9014: PHASEJAM

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S9014  
**Platforms:** Linux, Network Devices  
**Tactics:** Not specified

## Source description

[PHASEJAM](https://attack.mitre.org/software/S9014) is a dropper written as a bash shell script that modifies Ivanti Connect Secure appliance components. [PHASEJAM](https://attack.mitre.org/software/S9014) was first reported in January 2025. [PHASEJAM](https://attack.mitre.org/software/S9014) has previously been leveraged by People's Republic of China (PRC)- affiliated actors identified as UNC5221 and SYLVANITE.(Citation: Dragos SYLVANITE MuddyWater Electrum March 2026)(Citation: Google UNC5221 Ivanti January 2025)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S9014](https://attack.mitre.org/software/S9014)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
