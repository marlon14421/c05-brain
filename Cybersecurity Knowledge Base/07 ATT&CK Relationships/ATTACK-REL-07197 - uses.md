---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1091"
target_object: "T1087.004"
stix_relationship_id: "relationship--ed3fa28d-54ff-4b21-9924-58e5dcd94ac1"
---
# Relationship 7197: S1091 — uses → T1087.004

**Source object:** [[01 ATT&CK/S1091 - Pacu|S1091: Pacu]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1087.004 - Cloud Account|T1087.004: Cloud Account]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Pacu](https://attack.mitre.org/software/S1091) can enumerate IAM users, roles, and groups. (Citation: GitHub Pacu)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ed3fa28d-54ff-4b21-9924-58e5dcd94ac1`.
