---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1040"
target_object: "S0521"
stix_relationship_id: "relationship--c46ab316-6976-41ab-87ea-97f9d435b6cc"
---
# Relationship 5028: G1040 — uses → S0521

**Source object:** [[01 ATT&CK/G1040 - Play|G1040: Play]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0521 - BloodHound|S0521: BloodHound]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Trend Micro Ransomware Spotlight Play July 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c46ab316-6976-41ab-87ea-97f9d435b6cc`.
