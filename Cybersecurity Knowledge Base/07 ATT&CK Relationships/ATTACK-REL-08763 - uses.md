---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0026"
target_object: "S0124"
stix_relationship_id: "relationship--95842c88-c596-44c7-a16e-40d98e2457cc"
---
# Relationship 8763: G0026 — uses → S0124

**Source object:** [[01 ATT&CK/G0026 - APT18|G0026: APT18]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0124 - Pisloader|S0124: Pisloader]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Palo Alto DNS Requests)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--95842c88-c596-44c7-a16e-40d98e2457cc`.
