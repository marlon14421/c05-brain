---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0107"
source_url: "https://attack.mitre.org/detectionstrategies/DET0037#AN0107"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0107: Analytic 0107

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0107  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detects abnormal access to Safari credential stores (Keychain-backed) or Chrome/Firefox login databases. Observes processes executing `security dump-keychain` or directly reading credential files in `~/Library/Application Support`. Correlates file access with suspicious process ancestry or unsigned binaries.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0107](https://attack.mitre.org/detectionstrategies/DET0037#AN0107)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
