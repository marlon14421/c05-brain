---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0345"
source_url: "https://attack.mitre.org/detectionstrategies/DET0124#AN0345"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0345: Analytic 0345

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0345  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Process invokes a standard encoder (e.g., PowerShell -enc, certutil -encode, base64 via .NET/Invoke-Expression) or emits long Base64/hex literals → shortly followed by outbound network egress with high bytes_out:bytes_in ratio or HTTP headers/payloads containing Base64/MIME blocks.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0345](https://attack.mitre.org/detectionstrategies/DET0124#AN0345)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
