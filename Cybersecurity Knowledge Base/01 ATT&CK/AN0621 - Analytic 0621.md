---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0621"
source_url: "https://attack.mitre.org/detectionstrategies/DET0221#AN0621"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0621: Analytic 0621

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0621  
**Platforms:** macOS  
**Tactics:** Not specified

## Source description

Processes invoking AVFoundation or CoreAudio frameworks, accessing input devices via TCC logs or Unified Logs, followed by writing AIFF/WAV/MP3 files to disk.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0621](https://attack.mitre.org/detectionstrategies/DET0221#AN0621)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
