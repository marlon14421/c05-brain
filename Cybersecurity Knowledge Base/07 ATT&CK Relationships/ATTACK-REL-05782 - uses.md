---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0134"
target_object: "T1568"
stix_relationship_id: "relationship--23041edc-3136-49b7-8d08-311321455aa7"
---
# Relationship 5782: G0134 — uses → T1568

**Source object:** [[01 ATT&CK/G0134 - Transparent Tribe|G0134: Transparent Tribe]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1568 - Dynamic Resolution|T1568: Dynamic Resolution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Transparent Tribe](https://attack.mitre.org/groups/G0134) has used dynamic DNS services to set up C2.(Citation: Proofpoint Operation Transparent Tribe March 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--23041edc-3136-49b7-8d08-311321455aa7`.
