---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0574"
target_object: "T1001.001"
stix_relationship_id: "relationship--36855997-d730-48c6-bd43-7896c741cd6e"
---
# Relationship 6507: S0574 — uses → T1001.001

**Source object:** [[01 ATT&CK/S0574 - BendyBear|S0574: BendyBear]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1001.001 - Junk Data|T1001.001: Junk Data]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BendyBear](https://attack.mitre.org/software/S0574) has used byte randomization to obscure its behavior.(Citation: Unit42 BendyBear Feb 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--36855997-d730-48c6-bd43-7896c741cd6e`.
