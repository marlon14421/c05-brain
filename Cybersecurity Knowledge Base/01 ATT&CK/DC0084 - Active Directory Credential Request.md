---
type: "Data Component"
source: MITRE ATT&CK
id: "DC0084"
source_url: "https://attack.mitre.org/datacomponents/DC0084"
created: "2021-10-20"
modified: "2025-11-12"
---
# DC0084: Active Directory Credential Request

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Data Component  
**ATT&CK ID:** DC0084  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

Requests for authentication credentials via Kerberos or other methods like NTLM and LDAP queries. Examples: - Kerberos TGT and Service Tickets (Event IDs 4768, 4769) - NTLM Authentication Events - LDAP Bind Requests.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: DC0084](https://attack.mitre.org/datacomponents/DC0084)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
