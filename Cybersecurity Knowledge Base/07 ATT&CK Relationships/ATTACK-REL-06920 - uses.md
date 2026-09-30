---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9038"
target_object: "T1036"
stix_relationship_id: "relationship--c5fe3e1e-775e-4fe6-8a70-0a7e70835081"
---
# Relationship 6920: S9038 — uses → T1036

**Source object:** [[01 ATT&CK/S9038 - DynoWiper|S9038: DynoWiper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036 - Masquerading|T1036: Masquerading]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DynoWiper](https://attack.mitre.org/software/S9038) has been named after well-known files schtask.exe, schtask2.exe, and _update.exe.(Citation: CERT Polska)(Citation: ESET DynoWiper Update JAN 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c5fe3e1e-775e-4fe6-8a70-0a7e70835081`.
