---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0694"
target_object: "T1027"
stix_relationship_id: "relationship--def1a889-9341-4179-9d14-a5c10aa100b2"
---
# Relationship 6964: S0694 — uses → T1027

**Source object:** [[01 ATT&CK/S0694 - DRATzarus|S0694: DRATzarus]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DRATzarus](https://attack.mitre.org/software/S0694) can be partly encrypted with XOR.(Citation: ClearSky Lazarus Aug 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--def1a889-9341-4179-9d14-a5c10aa100b2`.
