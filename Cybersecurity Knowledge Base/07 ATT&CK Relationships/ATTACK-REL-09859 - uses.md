---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0229"
target_object: "T1055.012"
stix_relationship_id: "relationship--e039e3d4-2e3d-4e6e-902e-5e1834abe8e4"
---
# Relationship 9859: S0229 — uses → T1055.012

**Source object:** [[01 ATT&CK/S0229 - Orz|S0229: Orz]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.012 - Process Hollowing|T1055.012: Process Hollowing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Some [Orz](https://attack.mitre.org/software/S0229) versions have an embedded DLL known as MockDll that uses process hollowing and [Regsvr32](https://attack.mitre.org/techniques/T1218/010) to execute another payload.(Citation: Proofpoint Leviathan Oct 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e039e3d4-2e3d-4e6e-902e-5e1834abe8e4`.
