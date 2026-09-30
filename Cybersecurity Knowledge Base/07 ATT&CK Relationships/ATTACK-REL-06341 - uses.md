---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1004"
target_object: "T1078.004"
stix_relationship_id: "relationship--ec5caf8f-0fb8-4c3b-bd31-08804ff2214e"
---
# Relationship 6341: G1004 — uses → T1078.004

**Source object:** [[01 ATT&CK/G1004 - LAPSUS$|G1004: LAPSUS$]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1078.004 - Cloud Accounts|T1078.004: Cloud Accounts]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LAPSUS$](https://attack.mitre.org/groups/G1004) has used compromised credentials to access cloud assets within a target organization.(Citation: MSTIC DEV-0537 Mar 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ec5caf8f-0fb8-4c3b-bd31-08804ff2214e`.
