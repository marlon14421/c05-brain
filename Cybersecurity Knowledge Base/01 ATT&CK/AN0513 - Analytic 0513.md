---
type: "Detection Analytic"
source: MITRE ATT&CK
id: "AN0513"
source_url: "https://attack.mitre.org/detectionstrategies/DET0182#AN0513"
created: "2025-10-21"
modified: "2025-11-12"
---
# AN0513: Analytic 0513

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Detection Analytic  
**ATT&CK ID:** AN0513  
**Platforms:** Windows  
**Tactics:** Not specified

## Source description

Process or script enumerates network shares via CLI (net view/net share, PowerShell Get-SmbShare/WMI) or OS APIs (NetShareEnum/ srvsvc.NetShareEnumAll RPC) → bursts of outbound SMB/RPC connections (445/139, \\host\IPC$ / srvsvc) to many hosts inside a short window → optional follow-on file listing or copy operations.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: AN0513](https://attack.mitre.org/detectionstrategies/DET0182#AN0513)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
