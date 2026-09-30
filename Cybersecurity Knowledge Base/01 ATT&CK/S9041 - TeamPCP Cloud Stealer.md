---
type: "Malware"
source: MITRE ATT&CK
id: "S9041"
source_url: "https://attack.mitre.org/software/S9041"
created: "2026-07-01"
modified: "2026-07-31"
---
# S9041: TeamPCP Cloud Stealer

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Malware  
**ATT&CK ID:** S9041  
**Platforms:** Containers, Linux, macOS, SaaS, Windows  
**Tactics:** Not specified

## Source description

The [TeamPCP Cloud Stealer](https://attack.mitre.org/software/S9041) is a comprehensive filesystem credential stealer that can harvest, encrypt, and exfiltrate credentials from over 50 sensitive file paths across CI/CD, cloud, developer tooling, and container environments. The [TeamPCP Cloud Stealer](https://attack.mitre.org/software/S9041) was the primary payload used by [TeamPCP](https://attack.mitre.org/groups/G1056) in March 2026 during early stages of a cascading supply chain campaign targeting CI/CD workflows.(Citation: Wiz Trivy Compromise MAR 2026)(Citation: Aqua Security Trivy Compromise MAR 2026)(Citation: Aqua Security Blog Trivy Compromise APR 2026)(Citation: Sysdig TeamPCP MAR 2026)(Citation: Wiz TeamPCP KICS MAR 2026)(Citation: Palo Alto TeamPCP MAR 2026)(Citation: Google AI Threat Tracker MAY 2026)(Citation: FBI TeamPCP JUL 2026)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: S9041](https://attack.mitre.org/software/S9041)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
