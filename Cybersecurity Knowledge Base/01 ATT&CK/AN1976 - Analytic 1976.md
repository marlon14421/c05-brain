---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1976"
source_url: "https://attack.mitre.org/detectionstrategies/DET0844#AN1976"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1976: Analytic 1976

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1976  
**Platforms:** PRE  
**Tactics:** Not specified

## Source description

Consider use of services that may aid in the tracking of certificates in use on sites across the Internet. In some cases it may be possible to pivot on known pieces of certificate information to uncover other adversary infrastructure.(Citation: Splunk Kovar Certificates 2017) Detection efforts may be focused on related behaviors, such as [Web Protocols](https://attack.mitre.org/techniques/T1071/001) , [Asymmetric Cryptography](https://attack.mitre.org/techniques/T1573/002) , and/or [Install Root Certificate](https://attack.mitre.org/techniques/T1553/004) .

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1976](https://attack.mitre.org/detectionstrategies/DET0844#AN1976)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
