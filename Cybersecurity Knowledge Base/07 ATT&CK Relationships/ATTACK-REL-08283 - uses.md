---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0035"
target_object: "S0488"
stix_relationship_id: "relationship--a60d34fc-9c1e-4b36-a82b-56258445c7f0"
---
# Relationship 8283: G0035 — uses → S0488

**Source object:** [[01 ATT&CK/G0035 - Dragonfly|G0035: Dragonfly]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0488 - CrackMapExec|S0488: CrackMapExec]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Secureworks IRON LIBERTY July 2019)(Citation: US-CERT TA18-074A)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a60d34fc-9c1e-4b36-a82b-56258445c7f0`.
