---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0760"
source_url: "https://attack.mitre.org/detectionstrategies/DET0273#AN0760"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0760: Analytic 0760

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0760  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Processes like curl, wget, python, socat, or custom binaries initiating TLS/SSL sessions to non-standard destinations. Defender sees abnormal syscalls for connect(), loading of libssl libraries, and persistent outbound encrypted traffic from daemons not normally communicating externally.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0760](https://attack.mitre.org/detectionstrategies/DET0273#AN0760)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
