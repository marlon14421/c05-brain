---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1006"
target_object: "S0160"
stix_relationship_id: "relationship--8b18d3d9-154d-435a-a174-d84ef5961ec8"
---
# Relationship 6040: G1006 — uses → S0160

**Source object:** [[01 ATT&CK/G1006 - Earth Lusca|G1006: Earth Lusca]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0160 - certutil|S0160: certutil]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: TrendMicro EarthLusca 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8b18d3d9-154d-435a-a174-d84ef5961ec8`.
