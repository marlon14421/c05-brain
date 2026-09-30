---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1224"
target_object: "T1005"
stix_relationship_id: "relationship--e2966853-e5ce-4c28-a36f-61947a45c694"
---
# Relationship 7393: S1224 — uses → T1005

**Source object:** [[01 ATT&CK/S1224 - CASTLETAP|S1224: CASTLETAP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CASTLETAP](https://attack.mitre.org/software/S1224) can execute a C2 command to transfer files from victim machines.(Citation: Mandiant Fortinet Zero Day)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e2966853-e5ce-4c28-a36f-61947a45c694`.
