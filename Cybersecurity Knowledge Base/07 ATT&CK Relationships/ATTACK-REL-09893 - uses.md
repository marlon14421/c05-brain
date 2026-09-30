---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1054"
target_object: "T1204.002"
stix_relationship_id: "relationship--6b5d4e83-6ca4-4fa9-94a7-4068fcc8d3e6"
---
# Relationship 9893: G1054 — uses → T1204.002

**Source object:** [[01 ATT&CK/G1054 - MirrorFace|G1054: MirrorFace]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MirrorFace](https://attack.mitre.org/groups/G1054) has lured victims into opening crafted Word, Excel, and SFX files for execution.(Citation: Kaspersky LODEINFO OCT 2022)(Citation: ESET MirrorFace DEC 2022)(Citation: ITOCHU LODEINFO JAN 2024)(Citation: Trend Micro Earth Kasha Updates APR 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6b5d4e83-6ca4-4fa9-94a7-4068fcc8d3e6`.
