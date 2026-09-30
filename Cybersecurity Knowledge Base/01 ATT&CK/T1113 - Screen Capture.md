---
type: "Technique"
source: MITRE ATT&CK
id: "T1113"
source_url: "https://attack.mitre.org/techniques/T1113"
created: "2017-05-31"
modified: "2026-05-12"
---
# T1113: Screen Capture

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Technique  
**ATT&CK ID:** T1113  
**Platforms:** Linux, macOS, Windows  
**Tactics:** collection

## Source description

Adversaries may attempt to take screen captures of the desktop to gather information over the course of an operation. Screen capturing functionality may be included as a feature of a remote access tool used in post-compromise operations. Taking a screenshot is also typically possible through native utilities or API calls, such as CopyFromScreen , xwd , or screencapture .(Citation: CopyFromScreen .NET)(Citation: Antiquated Mac Malware)

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: T1113](https://attack.mitre.org/techniques/T1113)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
