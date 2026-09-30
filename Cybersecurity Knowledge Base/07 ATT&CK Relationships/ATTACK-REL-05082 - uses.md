---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1054"
target_object: "S9026"
stix_relationship_id: "relationship--a8aaec5a-fc14-421e-89b2-fb6dddb68f35"
---
# Relationship 5082: G1054 — uses → S9026

**Source object:** [[01 ATT&CK/G1054 - MirrorFace|G1054: MirrorFace]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S9026 - ROAMINGHOUSE|S9026: ROAMINGHOUSE]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MirrorFace](https://attack.mitre.org/groups/G1054) has used [ROAMINGHOUSE](https://attack.mitre.org/software/S9026) during operations.(Citation: Trend Micro Earth Kasha Updates APR 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a8aaec5a-fc14-421e-89b2-fb6dddb68f35`.
