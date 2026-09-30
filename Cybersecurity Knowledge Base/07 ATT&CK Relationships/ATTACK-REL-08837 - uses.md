---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1046"
target_object: "T1574.001"
stix_relationship_id: "relationship--b3b21563-6835-4478-a882-64ce66d5591b"
---
# Relationship 8837: S1046 — uses → T1574.001

**Source object:** [[01 ATT&CK/S1046 - PowGoop|S1046: PowGoop]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574.001 - DLL|T1574.001: DLL]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PowGoop](https://attack.mitre.org/software/S1046) can side-load `Goopdate.dll` into `GoogleUpdate.exe`.(Citation: DHS CISA AA22-055A MuddyWater February 2022)(Citation: CYBERCOM Iranian Intel Cyber January 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b3b21563-6835-4478-a882-64ce66d5591b`.
