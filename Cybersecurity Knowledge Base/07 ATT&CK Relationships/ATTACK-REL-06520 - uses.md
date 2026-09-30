---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1030"
target_object: "S1132"
stix_relationship_id: "relationship--338816c6-2f54-45e1-a329-a41b2da6a93e"
---
# Relationship 6520: G1030 — uses → S1132

**Source object:** [[01 ATT&CK/G1030 - Agrius|G1030: Agrius]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1132 - IPsec Helper|S1132: IPsec Helper]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Agrius](https://attack.mitre.org/groups/G1030) uses [IPsec Helper](https://attack.mitre.org/software/S1132) as a post-exploitation remote access tool framework.(Citation: SentinelOne Agrius 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--338816c6-2f54-45e1-a329-a41b2da6a93e`.
