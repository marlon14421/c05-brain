---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0060"
target_object: "S9027"
stix_relationship_id: "relationship--5a86d1f6-5f6a-4bd9-bc0c-d8c46d3233b8"
---
# Relationship 6648: C0060 — uses → S9027

**Source object:** [[01 ATT&CK/C0060 - Operation AkaiRyū|C0060: Operation AkaiRyū]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S9027 - ANELLDR|S9027: ANELLDR]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ANELLDR](https://attack.mitre.org/software/S9027) was used in [Operation AkaiRyū](https://attack.mitre.org/campaigns/C0060) as part of [UPPERCUT](https://attack.mitre.org/software/S0275) infection chains.(Citation: Trend Micro Earth Kasha Anel NOV 2024)(Citation: ESET MirrorFace 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5a86d1f6-5f6a-4bd9-bc0c-d8c46d3233b8`.
