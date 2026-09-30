---
type: "Malware"
source: MITRE ATT&CK
id: "S1161"
source_url: "https://attack.mitre.org/software/S1161"
created: "2024-09-20"
modified: "2026-05-12"
---
# S1161: BPFDoor

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1161  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

[BPFDoor](https://attack.mitre.org/software/S1161) is a Linux based passive long-term backdoor used by China-based threat actors. First seen in 2021, [BPFDoor](https://attack.mitre.org/software/S1161) is named after its usage of Berkley Packet Filter (BPF) to execute single task instructions. [BPFDoor](https://attack.mitre.org/software/S1161) supports multiple protocols for communicating with a C2 including TCP, UDP, and ICMP and can start local or reverse shells that bypass firewalls using iptables.(Citation: Sandfly BPFDoor 2022)(Citation: Deep Instinct BPFDoor 2023)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1161](https://attack.mitre.org/software/S1161)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
