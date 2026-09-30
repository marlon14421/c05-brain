---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0061"
target_object: "S0105"
stix_relationship_id: "relationship--76bd87d6-517e-4294-b4c5-a5a01308bf35"
---
# Relationship 5827: G0061 — uses → S0105

**Source object:** [[01 ATT&CK/G0061 - FIN8|G0061: FIN8]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0105 - dsquery|S0105: dsquery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: FireEye Know Your Enemy FIN8 Aug 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--76bd87d6-517e-4294-b4c5-a5a01308bf35`.
