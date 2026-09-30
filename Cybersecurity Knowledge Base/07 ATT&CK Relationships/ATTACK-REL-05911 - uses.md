---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0040"
target_object: "S0128"
stix_relationship_id: "relationship--f1456e13-5f3f-4dac-a002-2bd78c36348a"
---
# Relationship 5911: G0040 — uses → S0128

**Source object:** [[01 ATT&CK/G0040 - Patchwork|G0040: Patchwork]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0128 - BADNEWS|S0128: BADNEWS]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Forcepoint Monsoon)(Citation: TrendMicro Patchwork Dec 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f1456e13-5f3f-4dac-a002-2bd78c36348a`.
