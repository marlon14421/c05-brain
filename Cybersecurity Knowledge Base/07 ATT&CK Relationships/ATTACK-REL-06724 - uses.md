---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1015"
target_object: "T1070.004"
stix_relationship_id: "relationship--dd4ab207-a8d7-4b33-94bf-be87635cc853"
---
# Relationship 6724: S1015 — uses → T1070.004

**Source object:** [[01 ATT&CK/S1015 - Milan|S1015: Milan]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Milan](https://attack.mitre.org/software/S1015) can delete files via `C:\Windows\system32\cmd.exe /c ping 1.1.1.1 -n 1 -w 3000 > Nul & rmdir /s /q`.(Citation: ClearSky Siamesekitten August 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dd4ab207-a8d7-4b33-94bf-be87635cc853`.
