---
type: "Tool"
source: MITRE ATT&CK
id: "S9003"
source_url: "https://attack.mitre.org/software/S9003"
created: "2026-01-30"
modified: "2026-04-23"
---
# S9003: evilginx2

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Tool  
**ATT&CK ID:** S9003  
**Platforms:** IaaS, Identity Provider, Office Suite, SaaS  
**Tactics:** Not specified

## Source description

[evilginx2](https://attack.mitre.org/software/S9003) is an open-source adversary-in-the-middle (AiTM) attack framework based on the open-source nginx web server. [evilginx2](https://attack.mitre.org/software/S9003) can be used as a reverse proxy between victims and legitimate web services to intercept and capture credentials, authentication tokens, and session cookies.(Citation: Evilginx 2 July 2018)(Citation: Breakdev Evilginx 2.1 SEP 2018)(Citation: Sophos Evilginx MAR 2025)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S9003](https://attack.mitre.org/software/S9003)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
