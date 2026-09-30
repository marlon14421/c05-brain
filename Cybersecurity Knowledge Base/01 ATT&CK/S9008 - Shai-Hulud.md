---
type: "Malware"
source: MITRE ATT&CK
id: "S9008"
source_url: "https://attack.mitre.org/software/S9008"
created: "2026-04-09"
modified: "2026-04-24"
---
# S9008: Shai-Hulud

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S9008  
**Platforms:** Linux, SaaS, Windows  
**Tactics:** Not specified

## Source description

[Shai-Hulud](https://attack.mitre.org/software/S9008) is a supply chain worm, first reported in September 2025, that spreads through code repositories, including GitHub and NPM packages. It exploits CI/CD pipeline dependencies to propagate to victims and poisons the supply chain by publishing malicious packages. Once inside a victim environment, [Shai-Hulud](https://attack.mitre.org/software/S9008) steals credentials and access tokens from compromised repository accounts and exfiltrates them to attacker-controlled servers via encoded GitHub Actions workflows.(Citation: Palo Alto Unit 42 Shai-Hulud November 2025)(Citation: Microsoft Shai-Hulud December 2025)(Citation: Socket Shai-Hulud November 2025)(Citation: Socket Shai-Hulud Trufflehog September 2025)(Citation: Aikido Shai-Hulud September 2025)(Citation: Netskope Shai-Hulud November 2025)(Citation: Wiz Shai-Hulud September 2025)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S9008](https://attack.mitre.org/software/S9008)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
