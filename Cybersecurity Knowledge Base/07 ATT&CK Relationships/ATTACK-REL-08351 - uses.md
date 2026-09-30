---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1101"
target_object: "T1074.001"
stix_relationship_id: "relationship--959bda8e-6c64-4048-9c34-f8ccd64066e8"
---
# Relationship 8351: S1101 — uses → T1074.001

**Source object:** [[01 ATT&CK/S1101 - LoFiSe|S1101: LoFiSe]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1074.001 - Local Data Staging|T1074.001: Local Data Staging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LoFiSe](https://attack.mitre.org/software/S1101) can save files to be evaluated for further exfiltration in the `C:\Programdata\Microsoft\` and `C:\windows\temp\` folders. (Citation: Kaspersky ToddyCat Check Logs October 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--959bda8e-6c64-4048-9c34-f8ccd64066e8`.
