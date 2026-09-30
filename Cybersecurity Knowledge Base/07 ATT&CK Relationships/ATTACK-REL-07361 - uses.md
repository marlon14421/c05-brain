---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0276"
target_object: "T1555.002"
stix_relationship_id: "relationship--433418bb-0771-4b2d-9d6c-a153f6819798"
---
# Relationship 7361: S0276 — uses → T1555.002

**Source object:** [[01 ATT&CK/S0276 - Keydnap|S0276: Keydnap]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1555.002 - Securityd Memory|T1555.002: Securityd Memory]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Keydnap](https://attack.mitre.org/software/S0276) uses the keychaindump project to read securityd memory.(Citation: synack 2016 review)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--433418bb-0771-4b2d-9d6c-a153f6819798`.
