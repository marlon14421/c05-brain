---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0669"
target_object: "T1112"
stix_relationship_id: "relationship--1aae3796-86d5-4b31-ad21-e1dcc508a3b5"
---
# Relationship 7109: S0669 — uses → T1112

**Source object:** [[01 ATT&CK/S0669 - KOCTOPUS|S0669: KOCTOPUS]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1112 - Modify Registry|T1112: Modify Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[KOCTOPUS](https://attack.mitre.org/software/S0669) has added and deleted keys from the Registry.(Citation: MalwareBytes LazyScripter Feb 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1aae3796-86d5-4b31-ad21-e1dcc508a3b5`.
