---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1070"
target_object: "T1680"
stix_relationship_id: "relationship--8cef7b12-80af-4bb1-bf72-8eccd835d423"
---
# Relationship 7590: S1070 — uses → T1680

**Source object:** [[01 ATT&CK/S1070 - Black Basta|S1070: Black Basta]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1680 - Local Storage Discovery|T1680: Local Storage Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Black Basta](https://attack.mitre.org/software/S1070) can enumerate volumes.(Citation: Minerva Labs Black Basta May 2022)(Citation: Cyble Black Basta May 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8cef7b12-80af-4bb1-bf72-8eccd835d423`.
