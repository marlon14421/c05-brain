---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0096"
target_object: "S1051"
stix_relationship_id: "relationship--555b9de4-84c6-44f1-a6e6-b04a7e4ed374"
---
# Relationship 5706: G0096 — uses → S1051

**Source object:** [[01 ATT&CK/G0096 - APT41|G0096: APT41]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1051 - KEYPLUG|S1051: KEYPLUG]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Mandiant APT41)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--555b9de4-84c6-44f1-a6e6-b04a7e4ed374`.
