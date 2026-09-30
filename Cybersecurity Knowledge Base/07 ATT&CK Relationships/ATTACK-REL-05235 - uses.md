---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0091"
target_object: "S0363"
stix_relationship_id: "relationship--1567fbd3-5d2b-4040-a736-11f3d5e2139f"
---
# Relationship 5235: G0091 — uses → S0363

**Source object:** [[01 ATT&CK/G0091 - Silence|G0091: Silence]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0363 - Empire|S0363: Empire]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Group IB Silence Aug 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1567fbd3-5d2b-4040-a736-11f3d5e2139f`.
