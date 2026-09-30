---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0514"
target_object: "T1069.002"
stix_relationship_id: "relationship--a8b6a519-2159-46f0-916d-1f7a3d940eea"
---
# Relationship 7698: S0514 — uses → T1069.002

**Source object:** [[01 ATT&CK/S0514 - WellMess|S0514: WellMess]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1069.002 - Domain Groups|T1069.002: Domain Groups]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WellMess](https://attack.mitre.org/software/S0514) can identify domain group membership for the current user.(Citation: CISA WellMess July 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a8b6a519-2159-46f0-916d-1f7a3d940eea`.
