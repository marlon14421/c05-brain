---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0002"
target_object: "T1583.004"
stix_relationship_id: "relationship--b4ae0cf8-ad1f-4813-9e07-fc3faba1454e"
---
# Relationship 8593: C0002 — uses → T1583.004

**Source object:** [[01 ATT&CK/C0002 - Night Dragon|C0002: Night Dragon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1583.004 - Server|T1583.004: Server]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Night Dragon](https://attack.mitre.org/campaigns/C0002), threat actors purchased hosted services to use for C2.(Citation: McAfee Night Dragon)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b4ae0cf8-ad1f-4813-9e07-fc3faba1454e`.
