---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0466"
source_url: "https://attack.mitre.org/detectionstrategies/DET0164#AN0466"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0466: Analytic 0466

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0466  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detects adversary behavior where the command-line arguments of a running process are overwritten in memory to spoof the process name, typically replacing it with a benign or misleading string. The detection correlates unexpected null byte sequences, discrepancies between `/proc/ /cmdline` and process ancestry, and suspicious memory writes shortly after process start.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0466](https://attack.mitre.org/detectionstrategies/DET0164#AN0466)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
