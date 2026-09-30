---
type: "Malware"
source: MITRE ATT&CK
id: "S1203"
source_url: "https://attack.mitre.org/software/S1203"
created: "2025-02-18"
modified: "2025-04-15"
---
# S1203: J-magic

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1203  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

[J-magic](https://attack.mitre.org/software/S1203) is a custom variant of the [cd00r](https://attack.mitre.org/software/S1204) backdoor tailored to target Juniper routers that was first observed during the [J-magic Campaign](https://attack.mitre.org/campaigns/C0050) in mid-2023. [J-magic](https://attack.mitre.org/software/S1203) monitors TCP traffic for five predefined parameters or "magic packets" to be sent by the attackers before activating on compromised devices.(Citation: Lumen J-Magic JAN 2025)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1203](https://attack.mitre.org/software/S1203)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
