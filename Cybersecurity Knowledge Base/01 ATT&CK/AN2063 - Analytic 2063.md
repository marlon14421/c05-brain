---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN2063"
source_url: "https://attack.mitre.org/detectionstrategies/DET0920#AN2063"
created: "2026-04-23"
modified: "2026-04-24"
---
# AN2063: Analytic 2063

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN2063  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detection identifies execution of scripts or files that appear visually benign (low printable character ratio) but result in runtime decoding, dynamic evaluation, and subsequent process or network activity. Correlation links script execution with abnormal Unicode density and follow-on behavior such as child process creation or outbound connections.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN2063](https://attack.mitre.org/detectionstrategies/DET0920#AN2063)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
