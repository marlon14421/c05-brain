---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0397"
target_object: "T1112"
stix_relationship_id: "relationship--1f5c6a39-aa0b-469e-aabe-67e4d237b213"
---
# Relationship 6659: S0397 — uses → T1112

**Source object:** [[01 ATT&CK/S0397 - LoJax|S0397: LoJax]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1112 - Modify Registry|T1112: Modify Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LoJax](https://attack.mitre.org/software/S0397) has modified the Registry key ‘HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\BootExecute’ from ‘autocheck autochk *’ to ‘autocheck autoche *’ .(Citation: ESET LoJax Sept 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1f5c6a39-aa0b-469e-aabe-67e4d237b213`.
