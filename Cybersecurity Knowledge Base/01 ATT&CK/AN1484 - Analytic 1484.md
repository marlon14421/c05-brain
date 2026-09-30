---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1484"
source_url: "https://attack.mitre.org/detectionstrategies/DET0538#AN1484"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1484: Analytic 1484

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1484  
**Platforms:** Linux  
**Tactics:** Not specified

## Source description

sshd, socat, or custom binaries initiating port forwarding or encapsulating traffic (e.g., RDP, SMB) through SSH or HTTP. Defender sees abnormal connect/bind syscalls, encrypted traffic on ports typically used for non-encrypted services, and outlier traffic volume patterns.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1484](https://attack.mitre.org/detectionstrategies/DET0538#AN1484)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
