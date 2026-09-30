---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0059"
target_object: "T1070.004"
stix_relationship_id: "relationship--7f17927d-b371-42c4-bd68-0c5c57e3edab"
---
# Relationship 5684: G0059 — uses → T1070.004

**Source object:** [[01 ATT&CK/G0059 - Magic Hound|G0059: Magic Hound]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Magic Hound](https://attack.mitre.org/groups/G0059) has deleted and overwrote files to cover tracks.(Citation: Unit 42 Magic Hound Feb 2017)(Citation: FireEye APT35 2018)(Citation: DFIR Phosphorus November 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7f17927d-b371-42c4-bd68-0c5c57e3edab`.
