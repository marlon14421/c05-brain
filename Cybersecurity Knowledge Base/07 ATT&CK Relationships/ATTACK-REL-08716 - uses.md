---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1111"
target_object: "T1059.010"
stix_relationship_id: "relationship--7ccb8be7-7929-4186-8da6-48889be34952"
---
# Relationship 8716: S1111 — uses → T1059.010

**Source object:** [[01 ATT&CK/S1111 - DarkGate|S1111: DarkGate]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.010 - AutoHotKey & AutoIT|T1059.010: AutoHotKey & AutoIT]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DarkGate](https://attack.mitre.org/software/S1111) uses AutoIt scripts dropped to a hidden directory during initial installation phases, such as `test.au3`.(Citation: Ensilo Darkgate 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7ccb8be7-7929-4186-8da6-48889be34952`.
