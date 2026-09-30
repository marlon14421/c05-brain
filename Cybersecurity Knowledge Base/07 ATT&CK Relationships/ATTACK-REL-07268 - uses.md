---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1022"
target_object: "T1083"
stix_relationship_id: "relationship--bad38b14-93b7-42a3-b0a3-6170aa895734"
---
# Relationship 7268: G1022 — uses → T1083

**Source object:** [[01 ATT&CK/G1022 - ToddyCat|G1022: ToddyCat]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ToddyCat](https://attack.mitre.org/groups/G1022) has run scripts to enumerate recently modified documents having either a .pdf, .doc, .docx, .xls or .xlsx extension.(Citation: Kaspersky ToddyCat Check Logs October 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bad38b14-93b7-42a3-b0a3-6170aa895734`.
