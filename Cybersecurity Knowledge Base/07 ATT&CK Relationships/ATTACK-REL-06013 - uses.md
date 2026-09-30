---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0026"
target_object: "S0104"
stix_relationship_id: "relationship--a0bf4e01-2df1-4256-90fe-a504c76c6baf"
---
# Relationship 6013: C0026 — uses → S0104

**Source object:** [[01 ATT&CK/C0026 - C0026|C0026: C0026]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0104 - netstat|S0104: netstat]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Mandiant Suspected Turla Campaign February 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a0bf4e01-2df1-4256-90fe-a504c76c6baf`.
