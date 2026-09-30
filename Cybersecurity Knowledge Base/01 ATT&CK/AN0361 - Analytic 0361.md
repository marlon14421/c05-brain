---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0361"
source_url: "https://attack.mitre.org/detectionstrategies/DET0128#AN0361"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0361: Analytic 0361

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0361  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

Suspicious invocation of GUI utilities or scripts with suppressed or redirected windowing options. Defender view: detection of X11 or Wayland calls to spawn windows that do not appear on active displays, or use of nohup/screen/tmux to mask interactive shells.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0361](https://attack.mitre.org/detectionstrategies/DET0128#AN0361)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
