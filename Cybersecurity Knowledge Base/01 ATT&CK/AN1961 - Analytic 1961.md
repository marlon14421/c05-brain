---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1961"
source_url: "https://attack.mitre.org/detectionstrategies/DET0829#AN1961"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1961: Analytic 1961

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1961  
**Platforms:** PRE  
**Tactics:** Not specified

## Source description

Once adversaries leverage serverless functions as infrastructure (ex: for command and control), it may be possible to look for unique characteristics associated with adversary software, if known.(Citation: ThreatConnect Infrastructure Dec 2020) Much of this activity will take place outside the visibility of the target organization, making detection of this behavior difficult. Detection efforts may be focused on related stages of the adversary lifecycle.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1961](https://attack.mitre.org/detectionstrategies/DET0829#AN1961)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
