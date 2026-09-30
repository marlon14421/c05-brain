---
type: "Tool"
source: MITRE ATT&CK
id: "S9009"
source_url: "https://attack.mitre.org/software/S9009"
created: "2026-04-09"
modified: "2026-04-23"
---
# S9009: TruffleHog

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Tool  
**ATT&CK ID:** S9009  
**Platforms:** IaaS, Linux, SaaS, Windows  
**Tactics:** Not specified

## Source description

[TruffleHog](https://attack.mitre.org/software/S9009) is an open-source secrets-discovery tool that is used to search for credentials, API keys, and encryption keys across a variety of data sources and environments.(Citation: Black Hills Information Security TruffleHog January 2024)(Citation: Github TruffleSecurity Trufflehog April 2025) [TruffleHog](https://attack.mitre.org/software/S9009) has the ability to discover credentials and secrets stored in code repositories, git history, CI/CD pipelines, among other common storage locations to include filesystems and cloud storage buckets.(Citation: Black Hills Information Security TruffleHog January 2024)(Citation: Netskope Shai-Hulud November 2025)(Citation: Github TruffleSecurity Trufflehog April 2025) [TruffleHog](https://attack.mitre.org/software/S9009) was first released by its author in 2016.(Citation: Github TruffleSecurity Trufflehog April 2025)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S9009](https://attack.mitre.org/software/S9009)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
