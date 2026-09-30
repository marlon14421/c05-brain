---
type: "Malware"
source: MITRE ATT&CK
id: "S9043"
source_url: "https://attack.mitre.org/software/S9043"
created: "2026-07-29"
modified: "2026-07-31"
---
# S9043: Mini Shai-Hulud

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S9043  
**Platforms:** Containers, IaaS, Linux, macOS, SaaS, Windows  
**Tactics:** Not specified

## Source description

[Mini Shai-Hulud](https://attack.mitre.org/software/S9043) is a credential stealer and self-replicating supply chain worm, derived from [Shai-Hulud](https://attack.mitre.org/software/S9008), that has been used by [TeamPCP](https://attack.mitre.org/groups/G1056) to target Continuous Integration and Continuous Delivery/Deployment (CI/CD) workflows since at least 2026. [Mini Shai-Hulud](https://attack.mitre.org/software/S9043) can compromise credentials across multiple cloud, container, and AI configuration file paths and can use stolen npm and GitHub OIDC tokens to spread to other packages maintained by the compromised user. [Mini Shai-Hulud](https://attack.mitre.org/software/S9043) also has a targeted wiper component and has used multiple C2 and data exfiltration mechanisms.(Citation: Wiz Mini Shai-Hulud MAY 2026)(Citation: Trend Micro TeamPCP MAY 2026)(Citation: Hunt.io TeamPCP Toolkit MAY 2026)(Citation: Phoenix TeamPCP 20 MAY 2026)(Citation: Flashpoint Mini Shai-Hulud MAY 2026)(Citation: FBI TeamPCP JUL 2026)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S9043](https://attack.mitre.org/software/S9043)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
