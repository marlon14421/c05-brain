---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1030"
target_object: "S1134"
stix_relationship_id: "relationship--9073e616-bd4a-4546-9374-d2a7dc96efb4"
---
# Relationship 9279: G1030 — uses → S1134

**Source object:** [[01 ATT&CK/G1030 - Agrius|G1030: Agrius]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1134 - DEADWOOD|S1134: DEADWOOD]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DEADWOOD](https://attack.mitre.org/software/S1134) has been used by [Agrius](https://attack.mitre.org/groups/G1030) in wiping operations.(Citation: SentinelOne Agrius 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9073e616-bd4a-4546-9374-d2a7dc96efb4`.
