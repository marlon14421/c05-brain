---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1033"
target_object: "T1106"
stix_relationship_id: "relationship--6b580198-d882-4875-b1d5-ad937b95f12f"
---
# Relationship 6568: S1033 — uses → T1106

**Source object:** [[01 ATT&CK/S1033 - DCSrv|S1033: DCSrv]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DCSrv](https://attack.mitre.org/software/S1033) has used various Windows API functions, including `DeviceIoControl`, as part of its encryption process.(Citation: Checkpoint MosesStaff Nov 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6b580198-d882-4875-b1d5-ad937b95f12f`.
