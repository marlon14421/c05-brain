---
type: "Malware"
source: MITRE ATT&CK
id: "S9042"
source_url: "https://attack.mitre.org/software/S9042"
created: "2026-07-24"
modified: "2026-07-31"
---
# S9042: CanisterWorm

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S9042  
**Platforms:** Containers, Linux  
**Tactics:** Not specified

## Source description

[CanisterWorm](https://attack.mitre.org/software/S9042) is a self-propagating malware that has been used by [TeamPCP](https://attack.mitre.org/groups/G1056) in credential harvesting and software supply chain campaigns since at least 2026. [CanisterWorm](https://attack.mitre.org/software/S9042) has used npm credentials to infect software packages and propagate across developer ecosystems. [CanisterWorm](https://attack.mitre.org/software/S9042) has a targeted wiper component and can use decentralized C2 infrastructure implemented via an Internet Computer Protocol (ICP) blockchain canister.(Citation: Aikido TeamPCP Telnyx MAR 2026)(Citation: Palo Alto TeamPCP MAR 2026)(Citation: Aikido CanisterWorm MAR 2026)(Citation: Aikido TeamPCP Trivy MAR 2026)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S9042](https://attack.mitre.org/software/S9042)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
