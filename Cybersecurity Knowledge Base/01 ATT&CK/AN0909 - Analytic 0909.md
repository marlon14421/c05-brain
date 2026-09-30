---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0909"
source_url: "https://attack.mitre.org/detectionstrategies/DET0321#AN0909"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN0909: Analytic 0909

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0909  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Unusual execution of virtualization binaries (VBoxManage.exe, vmware-vmx.exe, vmwp.exe) with headless or suppressed notification arguments. Registry and service modifications linked to virtualization installs. Defender view: anomalies in process creation, service metadata, and registry writes tied to enabling hidden VMs.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0909](https://attack.mitre.org/detectionstrategies/DET0321#AN0909)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
