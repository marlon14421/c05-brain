---
type: "Threat Group"
source: MITRE ATT&CK
id: "G1020"
source_url: "https://attack.mitre.org/groups/G1020"
created: "2023-12-06"
modified: "2026-07-31"
---
# G1020: Mustard Tempest

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Threat Group  
**ATT&CK ID:** G1020  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

[Mustard Tempest](https://attack.mitre.org/groups/G1020) is an initial access broker that has operated the [SocGholish](https://attack.mitre.org/software/S1124) distribution network since at least 2017. [Mustard Tempest](https://attack.mitre.org/groups/G1020) has partnered with [Indrik Spider](https://attack.mitre.org/groups/G0119) to provide access for the download of additional malware including LockBit, [WastedLocker](https://attack.mitre.org/software/S0612), and remote access tools.(Citation: Microsoft Ransomware as a Service)(Citation: Microsoft Threat Actor Naming July 2023)(Citation: Secureworks Gold Prelude Profile)(Citation: SocGholish-update)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: G1020](https://attack.mitre.org/groups/G1020)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
