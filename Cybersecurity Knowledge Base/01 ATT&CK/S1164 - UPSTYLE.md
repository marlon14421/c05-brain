---
type: "Malware"
source: MITRE ATT&CK
id: "S1164"
source_url: "https://attack.mitre.org/software/S1164"
created: "2024-11-20"
modified: "2025-04-15"
---
# S1164: UPSTYLE

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S1164  
**Platforms:** Network Devices, Linux  
**Tactics:** Not specified

## Source description

[UPSTYLE](https://attack.mitre.org/software/S1164) is a Python-based backdoor associated with exploitation of Palo Alto firewalls using CVE-2024-3400 in early 2024. [UPSTYLE](https://attack.mitre.org/software/S1164) has only been observed in relation to this exploitation activity, which involved attempted install on compromised devices by the threat actor UTA0218.(Citation: Volexity UPSTYLE 2024)(Citation: Palo Alto MidnightEclipse APR 2024)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S1164](https://attack.mitre.org/software/S1164)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
