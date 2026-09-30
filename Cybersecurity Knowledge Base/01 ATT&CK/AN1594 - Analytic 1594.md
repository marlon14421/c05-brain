---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1594"
source_url: "https://attack.mitre.org/detectionstrategies/DET0578#AN1594"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1594: Analytic 1594

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1594  
**Platforms:** IaaS  
**Tactics:** Not specified

## Source description

Detection of suspicious enumeration of cloud storage objects via API calls such as AWS S3 ListObjectsV2, Azure List Blobs, or GCP ListObjects. Correlate access with account role, user context, and prior authentication activity to identify anomalous usage patterns (e.g., unusual account, unexpected regions, or large-scale enumeration in short time windows).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1594](https://attack.mitre.org/detectionstrategies/DET0578#AN1594)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
