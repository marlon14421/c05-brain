---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0060"
target_object: "T1585.003"
stix_relationship_id: "relationship--119e8f52-ad4b-431f-b50a-bd59263451be"
---
# Relationship 6127: C0060 — uses → T1585.003

**Source object:** [[01 ATT&CK/C0060 - Operation AkaiRyū|C0060: Operation AkaiRyū]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1585.003 - Cloud Accounts|T1585.003: Cloud Accounts]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Operation AkaiRyū](https://attack.mitre.org/campaigns/C0060), [MirrorFace](https://attack.mitre.org/groups/G1054) established OneDrive accounts to host malicious payloads.(Citation: ESET MirrorFace 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--119e8f52-ad4b-431f-b50a-bd59263451be`.
