---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0230"
target_object: "T1071.001"
stix_relationship_id: "relationship--a549ccf7-8610-4cf8-80d7-98491566c0cd"
---
# Relationship 7741: S0230 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0230 - ZeroT|S0230: ZeroT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ZeroT](https://attack.mitre.org/software/S0230) has used HTTP for C2.(Citation: Proofpoint TA459 April 2017)(Citation: Proofpoint ZeroT Feb 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a549ccf7-8610-4cf8-80d7-98491566c0cd`.
