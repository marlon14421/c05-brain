---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0352"
target_object: "T1571"
stix_relationship_id: "relationship--5a34e6af-f5e1-4191-aec0-06a92201f414"
---
# Relationship 8552: S0352 — uses → T1571

**Source object:** [[01 ATT&CK/S0352 - OSX_OCEANLOTUS.D|S0352: OSX_OCEANLOTUS.D]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1571 - Non-Standard Port|T1571: Non-Standard Port]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[OSX_OCEANLOTUS.D](https://attack.mitre.org/software/S0352) has used a custom binary protocol over TCP port 443 for C2.(Citation: Unit42 OceanLotus 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5a34e6af-f5e1-4191-aec0-06a92201f414`.
