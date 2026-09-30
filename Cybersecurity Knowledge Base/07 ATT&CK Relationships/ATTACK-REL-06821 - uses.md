---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0061"
target_object: "T1518.001"
stix_relationship_id: "relationship--1ce61b6a-b1fd-4e21-874a-774a1487fa12"
---
# Relationship 6821: G0061 — uses → T1518.001

**Source object:** [[01 ATT&CK/G0061 - FIN8|G0061: FIN8]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518.001 - Security Software Discovery|T1518.001: Security Software Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FIN8](https://attack.mitre.org/groups/G0061) has used Registry keys to detect and avoid executing in potential sandboxes.(Citation: FireEye Know Your Enemy FIN8 Aug 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1ce61b6a-b1fd-4e21-874a-774a1487fa12`.
