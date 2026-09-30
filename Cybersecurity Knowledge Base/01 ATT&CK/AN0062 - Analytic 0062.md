---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0062"
source_url: "https://attack.mitre.org/detectionstrategies/DET0021#AN0062"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0062: Analytic 0062

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0062  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Adversary executes systemctl or service stop targeting high-value services (e.g., mysql, sshd), possibly followed by rm or shred against data stores. Behavioral chain: sudo/su usage + stop command + /var/log/messages or syslog entries + file access/delete.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0062](https://attack.mitre.org/detectionstrategies/DET0021#AN0062)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
