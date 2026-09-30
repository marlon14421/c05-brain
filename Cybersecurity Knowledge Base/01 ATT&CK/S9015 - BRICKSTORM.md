---
type: "Malware"
source: MITRE ATT&CK
id: "S9015"
source_url: "https://attack.mitre.org/software/S9015"
created: "2026-04-16"
modified: "2026-04-23"
---
# S9015: BRICKSTORM

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S9015  
**Platforms:** ESXi, Linux, Network Devices, Windows  
**Tactics:** Not specified

## Source description

[BRICKSTORM](https://attack.mitre.org/software/S9015) is a cross-platform backdoor with variants written in Go and Rust that facilitates command and control, the ingress transfer of other malware, and the exfiltration of data.(Citation: CISA BRICKSTORM UNC5221 AR25-338A February 2026)(Citation: Picus Security BRICKSTORM UNC5221 October 2025)(Citation: Resecurity UNC5221 BRICKSTORM F5 Big-IP October 2025)(Citation: Google BRICKSTORM September 2025) [BRICKSTORM](https://attack.mitre.org/software/S9015) has also been created from a .NET application using ahead-of-time (AOT) compilation to blend in within victim environments.(Citation: CISA BRICKSTORM UNC5221 AR25-338A February 2026) [BRICKSTORM](https://attack.mitre.org/software/S9015) was first observed in April 2024.(Citation: Google UNC5221 BRICKSTORM SPAWNCHIMERA April 2024) [BRICKSTORM](https://attack.mitre.org/software/S9015) has previously been leveraged by People's Republic of China (PRC) state-nexus actors identified as UNC6201, UNC5221, WARP PANDA, PunyToad, and SYLVANITE.(Citation: Cloudflare 2026 Threat Report New Threat Actors March 2026)(Citation: CrowdStrike BRICKSTORM WARP PANDA UNC5221 December 2025)(Citation: CISA BRICKSTORM UNC5221 AR25-338A February 2026)(Citation: Dragos SYLVANITE MuddyWater Electrum March 2026)(Citation: NVISO BRICKSTORM April 2025)(Citation: Google BRICKSTORM GRIMBOLT UNC5221 UNC6201 February 2026)(Citation: Resecurity UNC5221 BRICKSTORM F5 Big-IP October 2025)(Citation: Google BRICKSTORM September 2025)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S9015](https://attack.mitre.org/software/S9015)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
