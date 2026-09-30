---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1042"
target_object: "T1571"
stix_relationship_id: "relationship--1080e9e7-df85-4f83-8b7f-5b5edd1e4aee"
---
# Relationship 8453: G1042 — uses → T1571

**Source object:** [[01 ATT&CK/G1042 - RedEcho|G1042: RedEcho]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1571 - Non-Standard Port|T1571: Non-Standard Port]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RedEcho](https://attack.mitre.org/groups/G1042) has used non-standard ports such as TCP 8080 for HTTP communication.(Citation: RecordedFuture RedEcho 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1080e9e7-df85-4f83-8b7f-5b5edd1e4aee`.
