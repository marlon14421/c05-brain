---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1149"
target_object: "T1106"
stix_relationship_id: "relationship--376f951c-844c-474b-b805-7f36caa07579"
---
# Relationship 8607: S1149 — uses → T1106

**Source object:** [[01 ATT&CK/S1149 - CHIMNEYSWEEP|S1149: CHIMNEYSWEEP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CHIMNEYSWEEP](https://attack.mitre.org/software/S1149) can use Windows APIs including `LoadLibrary` and `GetProcAddress`.(Citation: Mandiant ROADSWEEP August 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--376f951c-844c-474b-b805-7f36caa07579`.
