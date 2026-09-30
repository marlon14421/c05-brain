---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0589"
target_object: "T1070.004"
stix_relationship_id: "relationship--9fce9cf9-2795-4384-abb5-cb049b3d4329"
---
# Relationship 6406: S0589 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0589 - Sibot|S0589: Sibot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Sibot](https://attack.mitre.org/software/S0589) will delete itself if a certain server response is received.(Citation: MSTIC NOBELIUM Mar 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9fce9cf9-2795-4384-abb5-cb049b3d4329`.
