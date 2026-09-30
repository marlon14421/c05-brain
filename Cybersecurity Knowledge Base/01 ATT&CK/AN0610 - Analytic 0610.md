---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0610"
source_url: "https://attack.mitre.org/detectionstrategies/DET0218#AN0610"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0610: Analytic 0610

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0610  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Adversary manipulation of shared library paths, environment variables, or replacement of service binaries. Defender observes suspicious modifications in /etc/ld.so.preload, service config changes, or file writes replacing existing executables.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0610](https://attack.mitre.org/detectionstrategies/DET0218#AN0610)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
