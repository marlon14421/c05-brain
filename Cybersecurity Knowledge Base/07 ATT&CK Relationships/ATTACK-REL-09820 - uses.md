---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0115"
target_object: "S0591"
stix_relationship_id: "relationship--ab641f16-7ba7-452f-b737-786e8c20d815"
---
# Relationship 9820: G0115 — uses → S0591

**Source object:** [[01 ATT&CK/G0115 - GOLD SOUTHFIELD|G0115: GOLD SOUTHFIELD]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0591 - ConnectWise|S0591: ConnectWise]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Anomali Static Kitten February 2021)(Citation: Tetra Defense Sodinokibi March 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ab641f16-7ba7-452f-b737-786e8c20d815`.
