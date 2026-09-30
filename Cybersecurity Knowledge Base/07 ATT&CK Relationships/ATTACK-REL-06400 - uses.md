---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1203"
target_object: "T1070.003"
stix_relationship_id: "relationship--2200e547-9af6-4681-b8d3-b1cc3f2ef178"
---
# Relationship 6400: S1203 — uses → T1070.003

**Source object:** [[01 ATT&CK/S1203 - J-magic|S1203: J-magic]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.003 - Clear Command History|T1070.003: Clear Command History]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[J-magic](https://attack.mitre.org/software/S1203) can overwrite previously executed command line arguments.(Citation: Lumen J-Magic JAN 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2200e547-9af6-4681-b8d3-b1cc3f2ef178`.
