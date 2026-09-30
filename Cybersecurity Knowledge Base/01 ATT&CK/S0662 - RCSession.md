---
type: "Malware"
source: MITRE ATT&CK
id: "S0662"
source_url: "https://attack.mitre.org/software/S0662"
created: "2021-11-19"
modified: "2024-04-11"
---
# S0662: RCSession

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0662  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[RCSession](https://attack.mitre.org/software/S0662) is a backdoor written in C++ that has been in use since at least 2018 by [Mustang Panda](https://attack.mitre.org/groups/G0129) and by [Threat Group-3390](https://attack.mitre.org/groups/G0027) (Type II Backdoor).(Citation: Secureworks BRONZE PRESIDENT December 2019)(Citation: Trend Micro Iron Tiger April 2021)(Citation: Trend Micro DRBControl February 2020)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0662](https://attack.mitre.org/software/S0662)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
