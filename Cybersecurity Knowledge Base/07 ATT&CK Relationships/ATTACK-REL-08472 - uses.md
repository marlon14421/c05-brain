---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1018"
target_object: "T1012"
stix_relationship_id: "relationship--5da42f91-d58e-48bd-b8b2-3d35db7edcf2"
---
# Relationship 8472: S1018 — uses → T1012

**Source object:** [[01 ATT&CK/S1018 - Saint Bot|S1018: Saint Bot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1012 - Query Registry|T1012: Query Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Saint Bot](https://attack.mitre.org/software/S1018) has used `check_registry_keys` as part of its environmental checks.(Citation: Malwarebytes Saint Bot April 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5da42f91-d58e-48bd-b8b2-3d35db7edcf2`.
