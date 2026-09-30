---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0576"
target_object: "T1685"
stix_relationship_id: "relationship--064b2c99-1f7c-43d5-ab3e-892e598e2cac"
---
# Relationship 9936: S0576 — uses → T1685

**Source object:** [[01 ATT&CK/S0576 - MegaCortex|S0576: MegaCortex]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1685 - Disable or Modify Tools|T1685: Disable or Modify Tools]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MegaCortex](https://attack.mitre.org/software/S0576) was used to kill endpoint security processes.(Citation: IBM MegaCortex)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--064b2c99-1f7c-43d5-ab3e-892e598e2cac`.
