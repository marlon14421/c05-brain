---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0694"
target_object: "T1622"
stix_relationship_id: "relationship--50446870-ba6c-4d0c-b657-586a6cba8903"
---
# Relationship 9027: S0694 — uses → T1622

**Source object:** [[01 ATT&CK/S0694 - DRATzarus|S0694: DRATzarus]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1622 - Debugger Evasion|T1622: Debugger Evasion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DRATzarus](https://attack.mitre.org/software/S0694) can use `IsDebuggerPresent` to detect whether a debugger is present on a victim.(Citation: ClearSky Lazarus Aug 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--50446870-ba6c-4d0c-b657-586a6cba8903`.
