---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1030"
target_object: "T1218.010"
stix_relationship_id: "relationship--3283d0a8-5cd2-4548-a3bd-657d51684cd9"
---
# Relationship 6652: S1030 — uses → T1218.010

**Source object:** [[01 ATT&CK/S1030 - Squirrelwaffle|S1030: Squirrelwaffle]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.010 - Regsvr32|T1218.010: Regsvr32]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Squirrelwaffle](https://attack.mitre.org/software/S1030) has been executed using `regsvr32.exe`.(Citation: ZScaler Squirrelwaffle Sep 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3283d0a8-5cd2-4548-a3bd-657d51684cd9`.
