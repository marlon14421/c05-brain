---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0233"
source_url: "https://attack.mitre.org/detectionstrategies/DET0083#AN0233"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0233: Analytic 0233

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0233  
**Platforms:** Containers  
**Tactics:** Not specified

## Source description

Execution of container orchestration commands (e.g., `docker exec`, `kubectl exec`) or API-driven interactions with running containers from unauthorized hosts or non-standard user contexts. Defender sees programmatic or interactive command execution within containers outside expected CI/CD tools or automation frameworks, often followed by file writes, privilege escalation, or lateral discovery.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0233](https://attack.mitre.org/detectionstrategies/DET0083#AN0233)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
