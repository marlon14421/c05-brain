---
type: "Tactic"
source: MITRE ATT&CK
id: "TA0002"
source_url: "https://attack.mitre.org/tactics/TA0002"
created: "2018-10-17"
modified: "2025-04-25"
---
# TA0002: Execution

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Tactic  
**ATT&CK ID:** TA0002  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

The adversary is trying to run malicious code. Execution consists of techniques that result in adversary-controlled code running on a local or remote system. Techniques that run malicious code are often paired with techniques from all other tactics to achieve broader goals, like exploring a network or stealing data. For example, an adversary might use a remote access tool to run a PowerShell script that does Remote System Discovery.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: TA0002](https://attack.mitre.org/tactics/TA0002)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
