---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0414"
target_object: "T1105"
stix_relationship_id: "relationship--18d97b33-8ad5-426e-a390-72bea109bee0"
---
# Relationship 8938: S0414 — uses → T1105

**Source object:** [[01 ATT&CK/S0414 - BabyShark|S0414: BabyShark]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BabyShark](https://attack.mitre.org/software/S0414) has downloaded additional files from the C2.(Citation: Unit42 BabyShark Apr 2019)(Citation: CISA AA20-301A Kimsuky)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--18d97b33-8ad5-426e-a390-72bea109bee0`.
