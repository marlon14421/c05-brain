---
type: "Malware"
source: MITRE ATT&CK
id: "S1168"
source_url: "https://attack.mitre.org/software/S1168"
created: "2024-11-25"
modified: "2025-10-22"
---
# S1168: SampleCheck5000

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1168  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[SampleCheck5000](https://attack.mitre.org/software/S1168) is a downloader with multiple variants that was used by [OilRig](https://attack.mitre.org/groups/G0049) including during the [Outer Space](https://attack.mitre.org/campaigns/C0042) campaign to download and execute additional payloads. (Citation: ESET OilRig Campaigns Sep 2023)(Citation: ESET OilRig Downloaders DEC 2023)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1168](https://attack.mitre.org/software/S1168)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
