---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0016"
target_object: "S0677"
stix_relationship_id: "relationship--70ceb05c-ed86-4b51-bde0-2455662c30b7"
---
# Relationship 7815: G0016 — uses → S0677

**Source object:** [[01 ATT&CK/G0016 - APT29|G0016: APT29]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0677 - AADInternals|S0677: AADInternals]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: MSTIC Nobelium Oct 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--70ceb05c-ed86-4b51-bde0-2455662c30b7`.
