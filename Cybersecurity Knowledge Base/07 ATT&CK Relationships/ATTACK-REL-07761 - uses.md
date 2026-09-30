---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9038"
target_object: "T1678"
stix_relationship_id: "relationship--dd737a22-2390-4ffd-9ab7-4c9574fedfd7"
---
# Relationship 7761: S9038 — uses → T1678

**Source object:** [[01 ATT&CK/S9038 - DynoWiper|S9038: DynoWiper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1678 - Delay Execution|T1678: Delay Execution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DynoWiper](https://attack.mitre.org/software/S9038) has utilized a five-second delay using `Sleep(5000)` between two of the three phases of the attack that involves file overwriting, file deletion, and system reboot.(Citation: CERT Polska)(Citation: ESET DynoWiper Update JAN 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dd737a22-2390-4ffd-9ab7-4c9574fedfd7`.
