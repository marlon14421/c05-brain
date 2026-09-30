---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0625"
source_url: "https://attack.mitre.org/detectionstrategies/DET0223#AN0625"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0625: Analytic 0625

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0625  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Detects script or binary execution initiated via JAMF, Munki, or custom MDM agents outside of baseline, or JAMF launching new Terminal or osascript processes from remote command payloads.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0625](https://attack.mitre.org/detectionstrategies/DET0223#AN0625)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
