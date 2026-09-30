---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0446"
target_object: "T1106"
stix_relationship_id: "relationship--1790f5a1-b5d5-41a4-8da0-c75ed7a23b0d"
---
# Relationship 5505: S0446 — uses → T1106

**Source object:** [[01 ATT&CK/S0446 - Ryuk|S0446: Ryuk]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ryuk](https://attack.mitre.org/software/S0446) has used multiple native APIs including ShellExecuteW to run executables, GetWindowsDirectoryW to create folders, and VirtualAlloc , WriteProcessMemory , and CreateRemoteThread for process injection.(Citation: CrowdStrike Ryuk January 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1790f5a1-b5d5-41a4-8da0-c75ed7a23b0d`.
