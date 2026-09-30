---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0669"
target_object: "T1106"
stix_relationship_id: "relationship--be75f0ef-a8c8-42ec-b36b-670f7b528dd3"
---
# Relationship 9162: S0669 — uses → T1106

**Source object:** [[01 ATT&CK/S0669 - KOCTOPUS|S0669: KOCTOPUS]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[KOCTOPUS](https://attack.mitre.org/software/S0669) can use the `LoadResource` and `CreateProcessW` APIs for execution.(Citation: MalwareBytes LazyScripter Feb 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--be75f0ef-a8c8-42ec-b36b-670f7b528dd3`.
