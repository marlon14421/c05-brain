---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1223"
target_object: "T1071.001"
stix_relationship_id: "relationship--1c9ab3fb-f19b-4bc1-8afd-309c39672749"
---
# Relationship 6888: S1223 — uses → T1071.001

**Source object:** [[01 ATT&CK/S1223 - THINCRUST|S1223: THINCRUST]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[THINCRUST](https://attack.mitre.org/software/S1223) can use HTTP POST requests in C2 communications.(Citation: Mandiant Fortinet Zero Day)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1c9ab3fb-f19b-4bc1-8afd-309c39672749`.
