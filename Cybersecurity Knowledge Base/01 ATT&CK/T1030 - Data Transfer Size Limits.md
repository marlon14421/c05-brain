---
type: "Technique"
source: MITRE ATT&CK
id: "T1030"
source_url: "https://attack.mitre.org/techniques/T1030"
created: "2017-05-31"
modified: "2025-10-24"
---
# T1030: Data Transfer Size Limits

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Technique  
**ATT&CK ID:** T1030  
**Platforms:** Linux, macOS, Windows, ESXi  
**Tactics:** exfiltration

## Source description

An adversary may exfiltrate data in fixed size chunks instead of whole files or limit packet sizes below certain thresholds. This approach may be used to avoid triggering network data transfer threshold alerts.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: T1030](https://attack.mitre.org/techniques/T1030)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
