---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0348"
source_url: "https://attack.mitre.org/detectionstrategies/DET0124#AN0348"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0348: Analytic 0348

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0348  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

ESXi shell (BusyBox) or VMware utilities (openssl, python if present) used to Base64/hex encode data from datastore or config files → followed by abnormal egress from the host (NSX/flow logs) with asymmetric bytes_out or HTTPS posts to non-management endpoints.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0348](https://attack.mitre.org/detectionstrategies/DET0124#AN0348)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
