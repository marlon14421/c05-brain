---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1965"
source_url: "https://attack.mitre.org/detectionstrategies/DET0833#AN1965"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1965: Analytic 1965

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1965  
**Platforms:** PRE  
**Tactics:** Not specified

## Source description

Consider analyzing self-signed code signing certificates for features that may be associated with the adversary and/or their developers, such as the thumbprint, algorithm used, validity period, and common name. Malware repositories can also be used to identify additional samples associated with the adversary and identify patterns an adversary has used in crafting self-signed code signing certificates. Much of this activity will take place outside the visibility of the target organization, making detection of this behavior difficult. Detection efforts may be focused on related follow-on behavior, such as [Code Signing](https://attack.mitre.org/techniques/T1553/002) or [Install Root Certificate](https://attack.mitre.org/techniques/T1553/004).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1965](https://attack.mitre.org/detectionstrategies/DET0833#AN1965)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
