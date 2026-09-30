---
type: "Malware"
source: MITRE ATT&CK
id: "S0589"
source_url: "https://attack.mitre.org/software/S0589"
created: "2021-03-12"
modified: "2025-04-16"
---
# S0589: Sibot

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S0589  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[Sibot](https://attack.mitre.org/software/S0589) is dual-purpose malware written in VBScript designed to achieve persistence on a compromised system as well as download and execute additional payloads. Microsoft discovered three [Sibot](https://attack.mitre.org/software/S0589) variants in early 2021 during its investigation of [APT29](https://attack.mitre.org/groups/G0016) and the [SolarWinds Compromise](https://attack.mitre.org/campaigns/C0024).(Citation: MSTIC NOBELIUM Mar 2021)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S0589](https://attack.mitre.org/software/S0589)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
