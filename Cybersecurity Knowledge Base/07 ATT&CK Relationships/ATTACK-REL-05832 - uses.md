---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1007"
target_object: "S1027"
stix_relationship_id: "relationship--db7aadec-757b-49b3-8691-1f23b5c7c5fc"
---
# Relationship 5832: G1007 — uses → S1027

**Source object:** [[01 ATT&CK/G1007 - Aoqin Dragon|G1007: Aoqin Dragon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1027 - Heyoka Backdoor|S1027: Heyoka Backdoor]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: SentinelOne Aoqin Dragon June 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--db7aadec-757b-49b3-8691-1f23b5c7c5fc`.
