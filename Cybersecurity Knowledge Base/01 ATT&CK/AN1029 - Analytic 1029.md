---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN1029"
source_url: "https://attack.mitre.org/detectionstrategies/DET0362#AN1029"
created: "2025-10-21"
modified: "2025-10-21"
---
# AN1029: Analytic 1029

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN1029  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Detection of AppCert DLL abuse involves correlating registry modifications to the AppCertDLLs key with subsequent unexpected DLL load behavior during process creation events. Specifically, defenders can observe abnormal DLLs being loaded into standard Windows processes after changes to the 'AppCertDLLs' registry value. Monitoring CreateProcess-family API executions with injected DLLs and linking those DLLs back to recent registry edits is key to identifying misuse. This is often accompanied by elevated privileges and potential lateral movement or discovery behavior.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN1029](https://attack.mitre.org/detectionstrategies/DET0362#AN1029)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
