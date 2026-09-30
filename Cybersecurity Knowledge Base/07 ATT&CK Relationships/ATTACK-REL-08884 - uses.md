---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0088"
target_object: "S0029"
stix_relationship_id: "relationship--a8068bc5-7382-448b-9583-1f61edb68b96"
---
# Relationship 8884: G0088 — uses → S0029

**Source object:** [[01 ATT&CK/G0088 - TEMP.Veles|G0088: TEMP.Veles]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0029 - PsExec|S0029: PsExec]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: FireEye TRITON 2019)(Citation: Dragos Xenotime 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a8068bc5-7382-448b-9583-1f61edb68b96`.
