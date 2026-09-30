---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1233"
target_object: "T1074.001"
stix_relationship_id: "relationship--be20956b-6103-4bfc-a7c4-7e61cbc8cbcd"
---
# Relationship 8770: S1233 — uses → T1074.001

**Source object:** [[01 ATT&CK/S1233 - PAKLOG|S1233: PAKLOG]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1074.001 - Local Data Staging|T1074.001: Local Data Staging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PAKLOG](https://attack.mitre.org/software/S1233) has stored the captured data in a file located `C:\\Users\\Public\\Libraries\\record.txt`.(Citation: Zscaler PAKLOG CorkLog SplatCloak Splatdropper April 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--be20956b-6103-4bfc-a7c4-7e61cbc8cbcd`.
