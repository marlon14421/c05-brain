---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1184"
target_object: "T1082"
stix_relationship_id: "relationship--c4684b0f-86e1-4200-bd12-e9472f892779"
---
# Relationship 8781: S1184 — uses → T1082

**Source object:** [[01 ATT&CK/S1184 - BOLDMOVE|S1184: BOLDMOVE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BOLDMOVE](https://attack.mitre.org/software/S1184) performs system survey actions following initial execution.(Citation: Google Cloud BOLDMOVE 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c4684b0f-86e1-4200-bd12-e9472f892779`.
