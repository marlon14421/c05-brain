---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0514"
target_object: "T1071.004"
stix_relationship_id: "relationship--4f7ce20c-fab3-4dbd-be9f-c023d7b0bd90"
---
# Relationship 8065: S0514 — uses → T1071.004

**Source object:** [[01 ATT&CK/S0514 - WellMess|S0514: WellMess]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.004 - DNS|T1071.004: DNS]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WellMess](https://attack.mitre.org/software/S0514) has the ability to use DNS tunneling for C2 communications.(Citation: PWC WellMess July 2020)(Citation: NCSC APT29 July 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4f7ce20c-fab3-4dbd-be9f-c023d7b0bd90`.
