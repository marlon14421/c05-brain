---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0436"
source_url: "https://attack.mitre.org/detectionstrategies/DET0153#AN0436"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0436: Analytic 0436

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0436  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Unusual processes (e.g., powershell.exe, wscript.exe, mshta.exe) posting data to webhook endpoints (Discord, Slack, webhook.site) using HTTP POST/PUT requests. Defender perspective: suspicious process lineage followed by outbound HTTPS traffic to webhook domains.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0436](https://attack.mitre.org/detectionstrategies/DET0153#AN0436)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
