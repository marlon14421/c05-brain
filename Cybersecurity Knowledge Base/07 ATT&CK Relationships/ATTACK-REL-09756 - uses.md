---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0007"
target_object: "S0096"
stix_relationship_id: "relationship--6aeb6489-91f4-458c-b7f1-15b4025ee3fa"
---
# Relationship 9756: C0007 — uses → S0096

**Source object:** [[01 ATT&CK/C0007 - FunnyDream|C0007: FunnyDream]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0096 - Systeminfo|S0096: Systeminfo]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Bitdefender FunnyDream Campaign November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6aeb6489-91f4-458c-b7f1-15b4025ee3fa`.
