---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0078"
target_object: "S0385"
stix_relationship_id: "relationship--c3dd85c9-407c-4718-ba17-3c377c544dde"
---
# Relationship 7334: G0078 — uses → S0385

**Source object:** [[01 ATT&CK/G0078 - Gorgon Group|G0078: Gorgon Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0385 - njRAT|S0385: njRAT]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Unit 42 Gorgon Group Aug 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c3dd85c9-407c-4718-ba17-3c377c544dde`.
