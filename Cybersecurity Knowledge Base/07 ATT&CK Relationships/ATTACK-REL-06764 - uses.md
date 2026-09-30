---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1054"
target_object: "T1591"
stix_relationship_id: "relationship--29d8bf9e-da2f-4a82-9cbb-765cade6a58a"
---
# Relationship 6764: G1054 — uses → T1591

**Source object:** [[01 ATT&CK/G1054 - MirrorFace|G1054: MirrorFace]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1591 - Gather Victim Org Information|T1591: Gather Victim Org Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MirrorFace](https://attack.mitre.org/groups/G1054) has placed specific content in phishing emails to target members of particular political parties.(Citation: ESET MirrorFace DEC 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--29d8bf9e-da2f-4a82-9cbb-765cade6a58a`.
