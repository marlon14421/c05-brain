---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1122"
source_url: "https://attack.mitre.org/detectionstrategies/DET0400#AN1122"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1122: Analytic 1122

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1122  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Detects local daemons or scripts generating outbound DNS queries with long or frequent subdomains, indicative of DNS tunneling via tools like `iodine`, `dnscat2`, or `dig` from cronjobs or reverse shells.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1122](https://attack.mitre.org/detectionstrategies/DET0400#AN1122)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
