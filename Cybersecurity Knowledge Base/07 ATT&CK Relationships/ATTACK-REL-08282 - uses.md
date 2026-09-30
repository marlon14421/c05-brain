---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1013"
target_object: "T1071.001"
stix_relationship_id: "relationship--0d116456-322a-470c-a219-6d313f801b89"
---
# Relationship 8282: G1013 — uses → T1071.001

**Source object:** [[01 ATT&CK/G1013 - Metador|G1013: Metador]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Metador](https://attack.mitre.org/groups/G1013) has used HTTP for C2.(Citation: SentinelLabs Metador Sept 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0d116456-322a-470c-a219-6d313f801b89`.
