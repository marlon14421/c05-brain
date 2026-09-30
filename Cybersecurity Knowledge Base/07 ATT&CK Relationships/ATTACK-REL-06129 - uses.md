---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1176"
target_object: "T1564.001"
stix_relationship_id: "relationship--cc602d8f-9abf-4617-b33d-34bf91130f0c"
---
# Relationship 6129: S1176 — uses → T1564.001

**Source object:** [[01 ATT&CK/S1176 - attrib|S1176: attrib]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.001 - Hidden Files and Directories|T1564.001: Hidden Files and Directories]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[attrib](https://attack.mitre.org/software/S1176) can be used to make files or directories hidden.(Citation: Microsoft attrib 2023)(Citation: gbhackers Darkgate Malware 2024)(Citation: LogRhythm WannaCry)(Citation: Checkpoint WannaCry 2017)(Citation: Unit42 ComboJack 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cc602d8f-9abf-4617-b33d-34bf91130f0c`.
