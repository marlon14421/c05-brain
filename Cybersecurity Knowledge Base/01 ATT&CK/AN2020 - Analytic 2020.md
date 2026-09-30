---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN2020"
source_url: "https://attack.mitre.org/detectionstrategies/DET0888#AN2020"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN2020: Analytic 2020

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN2020  
**Platforms:** PRE  
**Tactics:** Not specified

## Source description

Internet scanners may be used to look for patterns associated with malicious content designed to collect host software information from visitors.(Citation: ThreatConnect Infrastructure Dec 2020)(Citation: ATT ScanBox) Much of this activity may have a very high occurrence and associated false positive rate, as well as potentially taking place outside the visibility of the target organization, making detection difficult for defenders. Detection efforts may be focused on related stages of the adversary lifecycle, such as during Initial Access.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN2020](https://attack.mitre.org/detectionstrategies/DET0888#AN2020)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
