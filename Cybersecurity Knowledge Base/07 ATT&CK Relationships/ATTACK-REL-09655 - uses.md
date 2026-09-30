---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0092"
target_object: "S0266"
stix_relationship_id: "relationship--239a4ed5-afe6-4d1d-8dfe-ee4df7bc01ba"
---
# Relationship 9655: G0092 — uses → S0266

**Source object:** [[01 ATT&CK/G0092 - TA505|G0092: TA505]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0266 - TrickBot|S0266: TrickBot]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Proofpoint TA505 Sep 2017)(Citation: IBM TA505 April 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--239a4ed5-afe6-4d1d-8dfe-ee4df7bc01ba`.
