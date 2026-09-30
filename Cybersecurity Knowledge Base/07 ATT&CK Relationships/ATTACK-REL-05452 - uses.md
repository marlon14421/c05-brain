---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1101"
target_object: "T1083"
stix_relationship_id: "relationship--734b4d88-1203-4ffc-8f49-393dfebfe162"
---
# Relationship 5452: S1101 — uses → T1083

**Source object:** [[01 ATT&CK/S1101 - LoFiSe|S1101: LoFiSe]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LoFiSe](https://attack.mitre.org/software/S1101) can monitor the file system to identify files less than 6.4 MB in size with file extensions including .doc, .docx, .xls, .xlsx, .ppt, .pptx, .pdf, .rtf, .tif, .odt, .ods, .odp, .eml, and .msg.(Citation: Kaspersky ToddyCat Check Logs October 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--734b4d88-1203-4ffc-8f49-393dfebfe162`.
