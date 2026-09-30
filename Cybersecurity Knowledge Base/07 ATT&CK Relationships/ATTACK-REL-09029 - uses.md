---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1020"
target_object: "T1566.002"
stix_relationship_id: "relationship--3fe304c6-4f26-42a9-b1f4-22635fd01245"
---
# Relationship 9029: G1020 — uses → T1566.002

**Source object:** [[01 ATT&CK/G1020 - Mustard Tempest|G1020: Mustard Tempest]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.002 - Spearphishing Link|T1566.002: Spearphishing Link]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mustard Tempest](https://attack.mitre.org/groups/G1020) has sent victims emails containing links to compromised websites.(Citation: SocGholish-update)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3fe304c6-4f26-42a9-b1f4-22635fd01245`.
