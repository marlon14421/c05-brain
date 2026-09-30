---
type: "Malware"
source: MITRE ATT&CK
id: "S1105"
source_url: "https://attack.mitre.org/software/S1105"
created: "2024-02-07"
modified: "2025-04-15"
---
# S1105: COATHANGER

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1105  
**Platforms:** Linux, Network Devices  
**Tactics:** Not specified

## Source description

[COATHANGER](https://attack.mitre.org/software/S1105) is a remote access tool (RAT) targeting FortiGate networking appliances. First used in 2023 in targeted intrusions against military and government entities in the Netherlands along with other victims, [COATHANGER](https://attack.mitre.org/software/S1105) was disclosed in early 2024, with a high confidence assessment linking this malware to a state-sponsored entity in the People's Republic of China. [COATHANGER](https://attack.mitre.org/software/S1105) is delivered after gaining access to a FortiGate device, with in-the-wild observations linked to exploitation of CVE-2022-42475. The name [COATHANGER](https://attack.mitre.org/software/S1105) is based on a unique string in the malware used to encrypt configuration files on disk: “She took his coat and hung it up” .(Citation: NCSC-NL COATHANGER Feb 2024)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1105](https://attack.mitre.org/software/S1105)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
