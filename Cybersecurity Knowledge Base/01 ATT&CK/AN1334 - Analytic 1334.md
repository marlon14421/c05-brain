---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1334"
source_url: "https://attack.mitre.org/detectionstrategies/DET0485#AN1334"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1334: Analytic 1334

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1334  
**Platforms:** ESXi  
**Tactics:** Not specified

## Source description

Monitor ESXi syslog and esxcli outputs for abnormal DNS resolver behavior, such as frequent domain-to-IP changes or unauthorized modifications of DNS settings used by management agents. Correlate domain lookups with short TTL values.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1334](https://attack.mitre.org/detectionstrategies/DET0485#AN1334)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
