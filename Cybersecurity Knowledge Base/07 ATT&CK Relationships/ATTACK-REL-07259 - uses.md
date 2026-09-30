---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0091"
target_object: "T1112"
stix_relationship_id: "relationship--396a5415-67aa-4ec6-ae27-6be641d69e15"
---
# Relationship 7259: G0091 — uses → T1112

**Source object:** [[01 ATT&CK/G0091 - Silence|G0091: Silence]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1112 - Modify Registry|T1112: Modify Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Silence](https://attack.mitre.org/groups/G0091) can create, delete, or modify a specified Registry key or value.(Citation: Group IB Silence Sept 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--396a5415-67aa-4ec6-ae27-6be641d69e15`.
