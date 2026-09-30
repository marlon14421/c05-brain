---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1957"
source_url: "https://attack.mitre.org/detectionstrategies/DET0825#AN1957"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1957: Analytic 1957

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1957  
**Platforms:** PRE  
**Tactics:** Not specified

## Source description

If infrastructure or patterns in the malicious web content utilized to deliver a [Drive-by Compromise](https://attack.mitre.org/techniques/T1189) have been previously identified, internet scanning may uncover when an adversary has staged web content for use in a strategic web compromise. Much of this activity will take place outside the visibility of the target organization, making detection of this behavior difficult. Detection efforts may be focused on other phases of the adversary lifecycle, such as [Drive-by Compromise](https://attack.mitre.org/techniques/T1189) or [Exploitation for Client Execution](https://attack.mitre.org/techniques/T1203).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1957](https://attack.mitre.org/detectionstrategies/DET0825#AN1957)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
