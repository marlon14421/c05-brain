---
type: "Malware"
source: MITRE ATT&CK
id: "S9035"
source_url: "https://attack.mitre.org/software/S9035"
created: "2026-04-21"
modified: "2026-05-12"
---
# S9035: LAMEHUG

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S9035  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[LAMEHUG](https://attack.mitre.org/software/S9035) is Python-based information stealer first identified in July 2025 by Ukraine's Computer Emergency Response Team (CERT-UA) in phishing emails targeting Ukrainian government officials. [LAMEHUG](https://attack.mitre.org/software/S9035) is the first known malware to integrate artificial intelligence (AI) directly into its attack workflow by querying large language models (LLMs) hosted on Hugging Face to dynamically generate reconnaissance, data theft, and system manipulation commands in real time. [LAMEHUG](https://attack.mitre.org/software/S9035) has been attributed to [APT28](https://attack.mitre.org/groups/G0007). (Citation: Splunk LAMEHUG SEP 2025)(Citation: Nov AI Threat Tracker)(Citation: Cato LAMEHUG JUL 2025)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S9035](https://attack.mitre.org/software/S9035)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
