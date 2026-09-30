---
type: "Campaign"
source: MITRE ATT&CK
id: "C0036"
source_url: "https://attack.mitre.org/campaigns/C0036"
created: "2024-07-17"
modified: "2026-07-31"
---
# C0036: Pikabot Distribution February 2024

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Campaign  
**ATT&CK ID:** C0036  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

[Pikabot](https://attack.mitre.org/software/S1145) was distributed in [Pikabot Distribution February 2024](https://attack.mitre.org/campaigns/C0036) using malicious emails with embedded links leading to malicious ZIP archives requiring user interaction for follow-on infection. The version of [Pikabot](https://attack.mitre.org/software/S1145) distributed featured significant changes over the 2023 variant, including reduced code complexity and simplified obfuscation mechanisms.(Citation: Elastic Pikabot 2024)(Citation: Zscaler Pikabot 2024)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: C0036](https://attack.mitre.org/campaigns/C0036)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
