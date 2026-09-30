---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1331"
source_url: "https://attack.mitre.org/detectionstrategies/DET0485#AN1331"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN1331: Analytic 1331

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1331  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Identify repeated DNS resolutions where the same domain name returns multiple IPs in short succession, combined with low TTL values and high query volume from unusual processes. Correlate with process lineage (e.g., Office apps spawning abnormal DNS lookups).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1331](https://attack.mitre.org/detectionstrategies/DET0485#AN1331)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
