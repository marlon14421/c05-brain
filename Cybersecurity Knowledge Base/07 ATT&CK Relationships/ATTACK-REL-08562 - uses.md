---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0061"
target_object: "S0196"
stix_relationship_id: "relationship--5b5f2424-ff4e-43ab-a08f-fab2b284041d"
---
# Relationship 8562: G0061 — uses → S0196

**Source object:** [[01 ATT&CK/G0061 - FIN8|G0061: FIN8]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0196 - PUNCHBUGGY|S0196: PUNCHBUGGY]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: FireEye Fin8 May 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5b5f2424-ff4e-43ab-a08f-fab2b284041d`.
