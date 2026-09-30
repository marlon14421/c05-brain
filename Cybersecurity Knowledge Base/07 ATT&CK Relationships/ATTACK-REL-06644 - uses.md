---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0484"
target_object: "T1071.001"
stix_relationship_id: "relationship--c3add97f-09bc-4c16-81ff-116106558487"
---
# Relationship 6644: S0484 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0484 - Carberp|S0484: Carberp]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Carberp](https://attack.mitre.org/software/S0484) has connected to C2 servers via HTTP.(Citation: Trusteer Carberp October 2010)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c3add97f-09bc-4c16-81ff-116106558487`.
