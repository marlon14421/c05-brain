---
type: "Threat Group"
source: MITRE ATT&CK
id: "G1056"
source_url: "https://attack.mitre.org/groups/G1056"
created: "2026-07-16"
modified: "2026-07-31"
---
# G1056: TeamPCP

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Threat Group  
**ATT&CK ID:** G1056  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

[TeamPCP](https://attack.mitre.org/groups/G1056) is a financially-motivated, cloud-native threat group that has been active since at least September 2025. Initially focused on ransomware and cryptocurrency theft, [TeamPCP](https://attack.mitre.org/groups/G1056) shifted in early 2026 to systematic, worm-driven credential theft and software supply chain attacks targeting Continuous Integration and Continuous Delivery (CI/CD) workflows. [TeamPCP](https://attack.mitre.org/groups/G1056) has monetized access through extortion and through partnerships with ransomware actors including Vect and CipherForce.(Citation: Wiz TeamPCP Profile MAY 2026)(Citation: Wiz Trivy Compromise MAR 2026)(Citation: Aqua Security Trivy Compromise MAR 2026)(Citation: Aqua Security Blog Trivy Compromise APR 2026)(Citation: Palo Alto TeamPCP MAR 2026)(Citation: Trend Micro TeamPCP MAY 2026)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: G1056](https://attack.mitre.org/groups/G1056)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
