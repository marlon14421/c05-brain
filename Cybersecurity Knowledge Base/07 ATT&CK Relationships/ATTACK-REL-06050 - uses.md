---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1026"
target_object: "T1071.001"
stix_relationship_id: "relationship--062e9fe2-bfc1-49dc-85b2-e8356757a2e8"
---
# Relationship 6050: S1026 — uses → T1071.001

**Source object:** [[01 ATT&CK/S1026 - Mongall|S1026: Mongall]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mongall](https://attack.mitre.org/software/S1026) can use HTTP for C2 communication.(Citation: SentinelOne Aoqin Dragon June 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--062e9fe2-bfc1-49dc-85b2-e8356757a2e8`.
