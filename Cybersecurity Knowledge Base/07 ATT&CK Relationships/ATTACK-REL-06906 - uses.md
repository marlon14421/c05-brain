---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0013"
target_object: "S0031"
stix_relationship_id: "relationship--9820c1e9-a414-4af1-a78c-aaf2cb164361"
---
# Relationship 6906: G0013 — uses → S0031

**Source object:** [[01 ATT&CK/G0013 - APT30|G0013: APT30]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0031 - BACKSPACE|S0031: BACKSPACE]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: FireEye APT30)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9820c1e9-a414-4af1-a78c-aaf2cb164361`.
