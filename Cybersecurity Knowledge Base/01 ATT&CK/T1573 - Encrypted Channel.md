---
type: "Technique"
source: MITRE ATT&CK
id: "T1573"
source_url: "https://attack.mitre.org/techniques/T1573"
created: "2020-03-16"
modified: "2025-10-24"
---
# T1573: Encrypted Channel

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Technique  
**ATT&CK ID:** T1573  
**Platforms:** ESXi, Linux, macOS, Network Devices, Windows  
**Tactics:** command-and-control

## Source description

Adversaries may employ an encryption algorithm to conceal command and control traffic rather than relying on any inherent protections provided by a communication protocol. Despite the use of a secure algorithm, these implementations may be vulnerable to reverse engineering if secret keys are encoded and/or generated within malware samples/configuration files.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: T1573](https://attack.mitre.org/techniques/T1573)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
