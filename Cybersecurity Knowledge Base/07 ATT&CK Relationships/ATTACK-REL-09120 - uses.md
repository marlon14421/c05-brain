---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0247"
target_object: "T1057"
stix_relationship_id: "relationship--b9e42e0a-e779-4491-b107-a064254a7da3"
---
# Relationship 9120: S0247 — uses → T1057

**Source object:** [[01 ATT&CK/S0247 - NavRAT|S0247: NavRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[NavRAT](https://attack.mitre.org/software/S0247) uses tasklist /v to check running processes.(Citation: Talos NavRAT May 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b9e42e0a-e779-4491-b107-a064254a7da3`.
