---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0083"
target_object: "S0447"
stix_relationship_id: "relationship--e8948840-b0a0-4c10-87f4-022720dc8dd9"
---
# Relationship 7533: G0083 — uses → S0447

**Source object:** [[01 ATT&CK/G0083 - SilverTerrier|G0083: SilverTerrier]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0447 - Lokibot|S0447: Lokibot]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Unit42 SilverTerrier 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e8948840-b0a0-4c10-87f4-022720dc8dd9`.
