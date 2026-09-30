---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0442"
target_object: "T1070.004"
stix_relationship_id: "relationship--83384e31-d9c6-46a0-956f-ee28d7d0cb89"
---
# Relationship 9003: S0442 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0442 - VBShower|S0442: VBShower]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[VBShower](https://attack.mitre.org/software/S0442) has attempted to complicate forensic analysis by deleting all the files contained in %APPDATA%\..\Local\Temporary Internet Files\Content.Word and %APPDATA%\..\Local Settings\Temporary Internet Files\Content.Word\ .(Citation: Kaspersky Cloud Atlas August 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--83384e31-d9c6-46a0-956f-ee28d7d0cb89`.
