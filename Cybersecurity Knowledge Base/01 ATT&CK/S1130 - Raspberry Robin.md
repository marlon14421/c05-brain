---
type: "Malware"
source: MITRE ATT&CK
id: "S1130"
source_url: "https://attack.mitre.org/software/S1130"
created: "2024-05-17"
modified: "2024-07-23"
---
# S1130: Raspberry Robin

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1130  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[Raspberry Robin](https://attack.mitre.org/software/S1130) is initial access malware first identified in September 2021, and active through early 2024. The malware is notable for spreading via infected USB devices containing a malicious LNK object that, on execution, retrieves remote hosted payloads for installation. [Raspberry Robin](https://attack.mitre.org/software/S1130) has been widely used against various industries and geographies, and as a precursor to information stealer, ransomware, and other payloads such as [SocGholish](https://attack.mitre.org/software/S1124), [Cobalt Strike](https://attack.mitre.org/software/S0154), [IcedID](https://attack.mitre.org/software/S0483), and [Bumblebee](https://attack.mitre.org/software/S1039).(Citation: TrendMicro RaspberryRobin 2022)(Citation: RedCanary RaspberryRobin 2022)(Citation: HP RaspberryRobin 2024) The DLL componenet in the [Raspberry Robin](https://attack.mitre.org/software/S1130) infection chain is also referred to as "Roshtyak."(Citation: Avast RaspberryRobin 2022) The name "Raspberry Robin" is used to refer to both the malware as well as the threat actor associated with its use, although the Raspberry Robin operators are also tracked as Storm-0856 by some vendors.(Citation: Microsoft RaspberryRobin 2022)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1130](https://attack.mitre.org/software/S1130)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
