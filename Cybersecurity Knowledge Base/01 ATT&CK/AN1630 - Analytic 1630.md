---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1630"
source_url: "https://attack.mitre.org/detectionstrategies/DET0592#AN1630"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1630: Analytic 1630

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1630  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

Defenders may observe adversary attempts to extract configuration data from management repositories by monitoring for anomalous SNMP queries, API calls, or protocol requests (e.g., NETCONF, RESTCONF) that enumerate system configuration. Suspicious sequences include repeated queries from untrusted IPs, abnormal query types requesting sensitive configuration data, or repository access occurring outside of normal administrative maintenance windows. Abnormal authentication attempts, sudden enumeration of device inventory, or bulk data transfer of configuration files may also be observed.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1630](https://attack.mitre.org/detectionstrategies/DET0592#AN1630)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
