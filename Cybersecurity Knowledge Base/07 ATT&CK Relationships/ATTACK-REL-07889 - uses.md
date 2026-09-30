---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1054"
target_object: "T1114.001"
stix_relationship_id: "relationship--e29acb85-fcd0-4286-b4bb-7ac2c8d72a5b"
---
# Relationship 7889: G1054 — uses → T1114.001

**Source object:** [[01 ATT&CK/G1054 - MirrorFace|G1054: MirrorFace]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1114.001 - Local Email Collection|T1114.001: Local Email Collection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MirrorFace](https://attack.mitre.org/groups/G1054) has exfiltrated stored emails from compromised hosts.(Citation: ESET MirrorFace DEC 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e29acb85-fcd0-4286-b4bb-7ac2c8d72a5b`.
