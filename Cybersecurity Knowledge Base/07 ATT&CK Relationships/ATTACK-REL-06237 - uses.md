---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1015"
target_object: "T1484.002"
stix_relationship_id: "relationship--247e3bf6-21c9-444e-81f7-a0e0f9eed04b"
---
# Relationship 6237: G1015 — uses → T1484.002

**Source object:** [[01 ATT&CK/G1015 - Scattered Spider|G1015: Scattered Spider]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1484.002 - Trust Modification|T1484.002: Trust Modification]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Scattered Spider](https://attack.mitre.org/groups/G1015) adds a federated identity provider to the victim’s SSO tenant and activates automatic account linking.(Citation: CISA Scattered Spider Advisory November 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--247e3bf6-21c9-444e-81f7-a0e0f9eed04b`.
