---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0462"
source_url: "https://attack.mitre.org/detectionstrategies/DET0162#AN0462"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0462: Analytic 0462

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0462  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Adversary installs/uses packet-capture or raw-socket capability (WinPcap/Npcap, wpcap/packet DLLs or raw socket attach) and sets a filter. A crafted inbound packet is observed; within a short window the host process that loaded capture libraries initiates an outbound connection (e.g., reverse shell) to the packet origin.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0462](https://attack.mitre.org/detectionstrategies/DET0162#AN0462)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
