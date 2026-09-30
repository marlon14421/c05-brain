---
type: "Malware"
source: MITRE ATT&CK
id: "S1167"
source_url: "https://attack.mitre.org/software/S1167"
created: "2024-11-25"
modified: "2025-04-17"
---
# S1167: AcidPour

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1167  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

[AcidPour](https://attack.mitre.org/software/S1167) is a variant of [AcidRain](https://attack.mitre.org/software/S1125) designed to impact a wider range of x86 architecture Linux devices. [AcidPour](https://attack.mitre.org/software/S1167) is an x86 ELF binary that expands on the targeted devices and locations in [AcidRain](https://attack.mitre.org/software/S1125) by including items such as Unsorted Block Image (UBI), Deice Mapper (DM), and various flash memory references. Based on this expanded targeting, [AcidPour](https://attack.mitre.org/software/S1167) can impact a variety of device types including IoT, networking, and ICS embedded device types.(Citation: SentinelOne AcidPour 2024) [AcidPour](https://attack.mitre.org/software/S1167) is a wiping payload associated with the [Sandworm Team](https://attack.mitre.org/groups/G0034) threat actor, and potentially linked to attacks against Ukrainian internet service providers (ISPs) in 2023.(Citation: CERT-UA TelecomAttack 2023)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1167](https://attack.mitre.org/software/S1167)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
