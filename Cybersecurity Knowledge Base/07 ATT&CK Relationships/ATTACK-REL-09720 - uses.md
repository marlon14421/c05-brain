---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1100"
target_object: "T1574.001"
stix_relationship_id: "relationship--6cbe59bb-e66e-456e-b230-5880ae6fd5ac"
---
# Relationship 9720: S1100 — uses → T1574.001

**Source object:** [[01 ATT&CK/S1100 - Ninja|S1100: Ninja]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574.001 - DLL|T1574.001: DLL]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ninja](https://attack.mitre.org/software/S1100) loaders can be side-loaded with legitimate and signed executables including the VLC.exe media player.(Citation: Kaspersky ToddyCat Check Logs October 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6cbe59bb-e66e-456e-b230-5880ae6fd5ac`.
