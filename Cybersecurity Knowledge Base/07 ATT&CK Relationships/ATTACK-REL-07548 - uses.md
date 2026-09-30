---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1004"
target_object: "T1578.003"
stix_relationship_id: "relationship--816b2bbb-9d91-4cf9-86b2-ff68a9f82969"
---
# Relationship 7548: G1004 — uses → T1578.003

**Source object:** [[01 ATT&CK/G1004 - LAPSUS$|G1004: LAPSUS$]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1578.003 - Delete Cloud Instance|T1578.003: Delete Cloud Instance]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LAPSUS$](https://attack.mitre.org/groups/G1004) has deleted the target's systems and resources in the cloud to trigger the organization's incident and crisis response process.(Citation: MSTIC DEV-0537 Mar 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--816b2bbb-9d91-4cf9-86b2-ff68a9f82969`.
