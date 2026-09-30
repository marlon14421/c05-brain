---
type: "Malware"
source: MITRE ATT&CK
id: "S9024"
source_url: "https://attack.mitre.org/software/S9024"
created: "2026-04-17"
modified: "2026-04-23"
---
# S9024: SPAWNCHIMERA

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S9024  
**Platforms:** Linux, Network Devices  
**Tactics:** Not specified

## Source description

[SPAWNCHIMERA](https://attack.mitre.org/software/S9024) is a backdoor that supports command and control and can inject malicious components into native processes.(Citation: CISA SPAWNCHIMERA RESURGE February 2026)(Citation: Google UNC5221 BRICKSTORM SPAWNCHIMERA April 2024)(Citation: JPCERT SPAWNCHIMERA Ivanti February 2025) [SPAWNCHIMERA](https://attack.mitre.org/software/S9024) It incorporates capabilities from multiple tools within the SPAWN malware family, including SPAWNANT, SPAWNMOLE, and SPAWNSNAIL.(Citation: Google UNC5221 Ivanti January 2025)(Citation: Google UNC5221 BRICKSTORM SPAWNCHIMERA April 2024)(Citation: JPCERT SPAWNCHIMERA Ivanti February 2025) [SPAWNCHIMERA](https://attack.mitre.org/software/S9024) was first reported in April 2024.(Citation: Google UNC5221 BRICKSTORM SPAWNCHIMERA April 2024) [SPAWNCHIMERA](https://attack.mitre.org/software/S9024) has been observed in activity attributed to People's Republic of China (PRC) state-sponsored threat actors, including UNC5221..(Citation: Google UNC5221 Ivanti January 2025)(Citation: Google UNC5221 Ivanti April 2025)(Citation: Google UNC5221 BRICKSTORM SPAWNCHIMERA April 2024)(Citation: Picus Security UNC5221 Ivanti May 2025)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S9024](https://attack.mitre.org/software/S9024)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
