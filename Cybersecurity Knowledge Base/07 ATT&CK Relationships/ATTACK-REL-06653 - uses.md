---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1034"
target_object: "T1584.004"
stix_relationship_id: "relationship--c75e753a-881a-40db-99d2-f7a7b2183606"
---
# Relationship 6653: G1034 — uses → T1584.004

**Source object:** [[01 ATT&CK/G1034 - Daggerfly|G1034: Daggerfly]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1584.004 - Server|T1584.004: Server]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Daggerfly](https://attack.mitre.org/groups/G1034) compromised web servers hosting updates for software as part of a supply chain intrusion.(Citation: ESET EvasivePanda 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c75e753a-881a-40db-99d2-f7a7b2183606`.
