---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1149"
target_object: "T1112"
stix_relationship_id: "relationship--ea54979f-3e4c-459c-bfaa-1435e36729e1"
---
# Relationship 5283: S1149 — uses → T1112

**Source object:** [[01 ATT&CK/S1149 - CHIMNEYSWEEP|S1149: CHIMNEYSWEEP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1112 - Modify Registry|T1112: Modify Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CHIMNEYSWEEP](https://attack.mitre.org/software/S1149) can use the Windows Registry Environment key to change the `%windir%` variable to point to `c:\Windows` to enable payload execution.(Citation: Mandiant ROADSWEEP August 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ea54979f-3e4c-459c-bfaa-1435e36729e1`.
