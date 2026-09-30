---
type: "Data Component"
source: MITRE ATT&CK
id: "DC0052"
source_url: "https://attack.mitre.org/datacomponents/DC0052"
created: "2021-10-20"
modified: "2025-10-21"
---
# DC0052: Social Media

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Data Component  
**ATT&CK ID:** DC0052  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

Established, compromised, or otherwise acquired by adversaries to conduct reconnaissance, influence operations, social engineering, or other cyber threats. *Data Collection Measures:* - API Monitoring - Social media APIs (e.g., Twitter API, Facebook Graph API) can extract behavioral patterns of accounts. - Web Scraping - Extracts public profile data, friend lists, or interactions to identify impersonation attempts. - Threat Intelligence Feeds - External feeds track malicious personas linked to disinformation campaigns or phishing. - OSINT Tools - Maltego, SpiderFoot, and OpenCTI can map social media persona relationships. - Endpoint Detection - EDR logs user behavior and alerts on suspicious social media interactions. - SIEM Logging - Detects access to known phishing pages or social media abuse via proxy logs. - Dark Web Monitoring - Identifies compromised social media credentials being sold.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: DC0052](https://attack.mitre.org/datacomponents/DC0052)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
