---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0431"
target_object: "T1027.002"
stix_relationship_id: "relationship--74f14668-7111-4f96-a307-4aac00d91cf4"
---
# Relationship 7767: S0431 — uses → T1027.002

**Source object:** [[01 ATT&CK/S0431 - HotCroissant|S0431: HotCroissant]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.002 - Software Packing|T1027.002: Software Packing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HotCroissant](https://attack.mitre.org/software/S0431) has used the open source UPX executable packer.(Citation: Carbon Black HotCroissant April 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--74f14668-7111-4f96-a307-4aac00d91cf4`.
