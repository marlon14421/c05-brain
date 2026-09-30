---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0768"
source_url: "https://attack.mitre.org/detectionstrategies/DET0275#AN0768"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0768: Analytic 0768

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0768  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

The adversary uses native utilities like base64, gzip, tar, or openssl to decode, decompress, or decrypt files that were previously staged or downloaded. These tools may be chained with curl/wget and executed via bash/zsh, often to extract an embedded payload or reverse shell script.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0768](https://attack.mitre.org/detectionstrategies/DET0275#AN0768)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
