---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0033"
target_object: "T1007"
stix_relationship_id: "relationship--720be590-5ea0-43b6-8360-fa75dd4d1a67"
---
# Relationship 8301: G0033 — uses → T1007

**Source object:** [[01 ATT&CK/G0033 - Poseidon Group|G0033: Poseidon Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1007 - System Service Discovery|T1007: System Service Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

After compromising a victim, [Poseidon Group](https://attack.mitre.org/groups/G0033) discovers all running services.(Citation: Kaspersky Poseidon Group)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--720be590-5ea0-43b6-8360-fa75dd4d1a67`.
