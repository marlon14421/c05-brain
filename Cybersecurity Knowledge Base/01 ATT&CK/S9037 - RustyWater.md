---
type: "Malware"
source: MITRE ATT&CK
id: "S9037"
source_url: "https://attack.mitre.org/software/S9037"
created: "2026-04-21"
modified: "2026-05-12"
---
# S9037: RustyWater

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S9037  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

[RustyWater](https://attack.mitre.org/software/S9037) is a Rust-based implant used by [MuddyWater](https://attack.mitre.org/groups/G0069). Historically, [MuddyWater](https://attack.mitre.org/groups/G0069) has used PowerShell-based tools and [RustyWater](https://attack.mitre.org/software/S9037) reflects a shift in tooling, demonstrating better techniques for defense evasion and reverse engineering.(Citation: CloudSEK_RustyWater_Jan2026)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S9037](https://attack.mitre.org/software/S9037)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
