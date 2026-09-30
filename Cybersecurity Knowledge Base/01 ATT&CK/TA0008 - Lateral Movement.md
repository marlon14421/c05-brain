---
type: "Tactic"
source: MITRE ATT&CK
id: "TA0008"
source_url: "https://attack.mitre.org/tactics/TA0008"
created: "2018-10-17"
modified: "2025-08-11"
---
# TA0008: Lateral Movement

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Tactic  
**ATT&CK ID:** TA0008  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

The adversary is trying to move through your environment. Lateral Movement consists of techniques that adversaries use to enter and control remote systems on a network. Following through on their primary objective often requires exploring the network to find their target, then pivoting through multiple systems and accounts to gain access to it. Adversaries might install their own remote access tools to accomplish Lateral Movement or use legitimate credentials with native network and operating system tools, which may be stealthier.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: TA0008](https://attack.mitre.org/tactics/TA0008)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
