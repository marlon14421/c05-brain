---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0347"
source_url: "https://attack.mitre.org/detectionstrategies/DET0124#AN0347"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0347: Analytic 0347

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0347  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Processes use base64/xxd/openssl/python Objective‑C APIs to encode data (seen in EndpointSecurity exec events or Unified Logs) → quick outbound connections with large bytes_out or HTTP POSTs carrying Base64/MIME bodies.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0347](https://attack.mitre.org/detectionstrategies/DET0124#AN0347)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
