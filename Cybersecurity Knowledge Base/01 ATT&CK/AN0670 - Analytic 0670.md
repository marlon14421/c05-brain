---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0670"
source_url: "https://attack.mitre.org/detectionstrategies/DET0239#AN0670"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0670: Analytic 0670

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0670  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

Detection of syslog configuration tampering using esxcli system syslog config set or reload. Defender correlates command execution with absence of syslog forwarding activity.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0670](https://attack.mitre.org/detectionstrategies/DET0239#AN0670)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
