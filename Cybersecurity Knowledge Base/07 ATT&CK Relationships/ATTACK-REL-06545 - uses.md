---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0574"
target_object: "T1027.013"
stix_relationship_id: "relationship--9d0eda8b-7696-4b22-a31e-6761e42bc2ae"
---
# Relationship 6545: S0574 — uses → T1027.013

**Source object:** [[01 ATT&CK/S0574 - BendyBear|S0574: BendyBear]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BendyBear](https://attack.mitre.org/software/S0574) has encrypted payloads using RC4 and XOR.(Citation: Unit42 BendyBear Feb 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9d0eda8b-7696-4b22-a31e-6761e42bc2ae`.
