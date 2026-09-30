---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0093"
target_object: "S0590"
stix_relationship_id: "relationship--cc443415-7c35-49ab-92a9-3d0cfa68c7b2"
---
# Relationship 6657: G0093 — uses → S0590

**Source object:** [[01 ATT&CK/G0093 - GALLIUM|G0093: GALLIUM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0590 - NBTscan|S0590: NBTscan]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Cybereason Soft Cell June 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cc443415-7c35-49ab-92a9-3d0cfa68c7b2`.
