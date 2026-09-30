---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1043"
target_object: "T1560.001"
stix_relationship_id: "relationship--27fe3870-1ce3-4f62-be7c-6da08d09643c"
---
# Relationship 5523: S1043 — uses → T1560.001

**Source object:** [[01 ATT&CK/S1043 - ccf32|S1043: ccf32]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1560.001 - Archive via Utility|T1560.001: Archive via Utility]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ccf32](https://attack.mitre.org/software/S1043) has used `xcopy \\ \c$\users\public\path.7z c:\users\public\bin\ .7z /H /Y` to archive collected files.(Citation: Bitdefender FunnyDream Campaign November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--27fe3870-1ce3-4f62-be7c-6da08d09643c`.
