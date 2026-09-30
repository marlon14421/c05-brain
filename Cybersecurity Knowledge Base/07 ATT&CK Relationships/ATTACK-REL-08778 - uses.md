---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0138"
target_object: "S0032"
stix_relationship_id: "relationship--daabfd4e-f873-4afc-8f39-fc5daf7cd71a"
---
# Relationship 8778: G0138 — uses → S0032

**Source object:** [[01 ATT&CK/G0138 - Andariel|G0138: Andariel]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0032 - gh0st RAT|S0032: gh0st RAT]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: AhnLab Andariel Subgroup of Lazarus June 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--daabfd4e-f873-4afc-8f39-fc5daf7cd71a`.
