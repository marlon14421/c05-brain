---
type: "Malware"
source: MITRE ATT&CK
id: "S0600"
source_url: "https://attack.mitre.org/software/S0600"
created: "2021-04-06"
modified: "2025-04-25"
---
# S0600: Doki

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0600  
**Platforms:** Linux, Containers  
**Tactics:** Not specified

## Source description

[Doki](https://attack.mitre.org/software/S0600) is a backdoor that uses a unique Dogecoin-based Domain Generation Algorithm and was first observed in July 2020. [Doki](https://attack.mitre.org/software/S0600) was used in conjunction with the [ngrok](https://attack.mitre.org/software/S0508) Mining Botnet in a campaign that targeted Docker servers in cloud platforms. (Citation: Intezer Doki July 20)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0600](https://attack.mitre.org/software/S0600)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
