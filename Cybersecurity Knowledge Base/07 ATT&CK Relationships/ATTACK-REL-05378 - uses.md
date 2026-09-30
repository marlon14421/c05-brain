---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0114"
target_object: "S0521"
stix_relationship_id: "relationship--5db02c00-0d28-4831-bad9-66737bb62eca"
---
# Relationship 5378: G0114 — uses → S0521

**Source object:** [[01 ATT&CK/G0114 - Chimera|G0114: Chimera]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0521 - BloodHound|S0521: BloodHound]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Cycraft Chimera April 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5db02c00-0d28-4831-bad9-66737bb62eca`.
