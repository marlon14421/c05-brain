---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1031"
target_object: "T1684.001"
stix_relationship_id: "relationship--61035d89-bac7-4267-829f-a898eeb41f11"
---
# Relationship 7680: G1031 — uses → T1684.001

**Source object:** [[01 ATT&CK/G1031 - Saint Bear|G1031: Saint Bear]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1684.001 - Impersonation|T1684.001: Impersonation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Saint Bear](https://attack.mitre.org/groups/G1031) has impersonated government and related entities in both phishing activity and developing web sites with malicious links that mimic legitimate resources.(Citation: Cadet Blizzard emerges as novel threat actor)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--61035d89-bac7-4267-829f-a898eeb41f11`.
