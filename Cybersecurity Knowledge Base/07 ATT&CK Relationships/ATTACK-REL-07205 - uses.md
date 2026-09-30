---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1044"
target_object: "T1070"
stix_relationship_id: "relationship--3022f4d3-c2b9-4937-96ae-f4d86ba89bb8"
---
# Relationship 7205: G1044 — uses → T1070

**Source object:** [[01 ATT&CK/G1044 - APT42|G1044: APT42]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070 - Indicator Removal|T1070: Indicator Removal]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT42](https://attack.mitre.org/groups/G1044) has cleared Chrome browser history.(Citation: Mandiant APT42-untangling)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3022f4d3-c2b9-4937-96ae-f4d86ba89bb8`.
