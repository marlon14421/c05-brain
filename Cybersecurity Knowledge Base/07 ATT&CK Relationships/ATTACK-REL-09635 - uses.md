---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0033"
target_object: "T1057"
stix_relationship_id: "relationship--c6f81350-a410-4ac7-a4b0-58bd4a9c1d9e"
---
# Relationship 9635: G0033 — uses → T1057

**Source object:** [[01 ATT&CK/G0033 - Poseidon Group|G0033: Poseidon Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

After compromising a victim, [Poseidon Group](https://attack.mitre.org/groups/G0033) lists all running processes.(Citation: Kaspersky Poseidon Group)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c6f81350-a410-4ac7-a4b0-58bd4a9c1d9e`.
