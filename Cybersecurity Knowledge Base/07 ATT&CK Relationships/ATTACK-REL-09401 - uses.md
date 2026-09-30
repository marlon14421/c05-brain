---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0049"
target_object: "S0258"
stix_relationship_id: "relationship--fa224c64-2157-4c2f-9f9c-451a3923cc42"
---
# Relationship 9401: G0049 — uses → S0258

**Source object:** [[01 ATT&CK/G0049 - OilRig|G0049: OilRig]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0258 - RGDoor|S0258: RGDoor]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Unit 42 RGDoor Jan 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fa224c64-2157-4c2f-9f9c-451a3923cc42`.
