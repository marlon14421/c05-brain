---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0140"
source_url: "https://attack.mitre.org/detectionstrategies/DET0051#AN0140"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0140: Analytic 0140

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0140  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Adversaries writing or moving payloads into directories configured as AV/EDR exclusion paths (e.g., /tmp, /var/lib, or custom directories from auditd exclusion rules). Defender perspective: detect file creation in paths matching known exclusions correlated with unusual parent processes.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0140](https://attack.mitre.org/detectionstrategies/DET0051#AN0140)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
