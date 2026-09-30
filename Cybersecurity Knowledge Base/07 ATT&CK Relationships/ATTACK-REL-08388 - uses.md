---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0024"
target_object: "S0067"
stix_relationship_id: "relationship--0cde085d-12ca-4cde-a99c-c37d63d7dc2e"
---
# Relationship 8388: G0024 — uses → S0067

**Source object:** [[01 ATT&CK/G0024 - Putter Panda|G0024: Putter Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0067 - pngdowner|S0067: pngdowner]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: CrowdStrike Putter Panda)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0cde085d-12ca-4cde-a99c-c37d63d7dc2e`.
