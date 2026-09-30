---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0050"
target_object: "S0039"
stix_relationship_id: "relationship--e725bb68-9fe3-4c43-8ef5-57d57b40b066"
---
# Relationship 5149: G0050 — uses → S0039

**Source object:** [[01 ATT&CK/G0050 - APT32|G0050: APT32]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0039 - Net|S0039: Net]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Cybereason Cobalt Kitty 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e725bb68-9fe3-4c43-8ef5-57d57b40b066`.
