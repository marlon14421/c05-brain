---
type: "Malware"
source: MITRE ATT&CK
id: "S9028"
source_url: "https://attack.mitre.org/software/S9028"
created: "2026-04-19"
modified: "2026-05-12"
---
# S9028: PHPsert

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S9028  
**Platforms:** Network Devices  
**Tactics:** Not specified

## Source description

[PHPsert](https://attack.mitre.org/software/S9028) is a webshell used to execute PHP code that has been in use since at least 2023 against targets in Japan, Singapore, Peru, Taiwan, Iran, Republic of Korea, and the Philippines. [PHPsert](https://attack.mitre.org/software/S9028) is not typically deployed as a standalone but integrated into web content such as text editors and content management systems.(Citation: sentinelone operationDigitalEye Dec 2024)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S9028](https://attack.mitre.org/software/S9028)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
