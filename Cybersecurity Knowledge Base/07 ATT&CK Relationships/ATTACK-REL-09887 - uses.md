---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9024"
target_object: "T1574.006"
stix_relationship_id: "relationship--7beb0954-f5b9-4c41-a732-c4ebb961148a"
---
# Relationship 9887: S9024 — uses → T1574.006

**Source object:** [[01 ATT&CK/S9024 - SPAWNCHIMERA|S9024: SPAWNCHIMERA]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574.006 - Dynamic Linker Hijacking|T1574.006: Dynamic Linker Hijacking]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SPAWNCHIMERA](https://attack.mitre.org/software/S9024) has been compiled as a Position Independent Executable (PIE) to use a third-party library for injection.(Citation: Google UNC5221 BRICKSTORM SPAWNCHIMERA April 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7beb0954-f5b9-4c41-a732-c4ebb961148a`.
