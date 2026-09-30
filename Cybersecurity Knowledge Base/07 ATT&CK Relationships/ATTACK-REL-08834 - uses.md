---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1065"
target_object: "T1005"
stix_relationship_id: "relationship--71bc9a2e-4536-4b84-9997-126cc4c065bf"
---
# Relationship 8834: S1065 — uses → T1005

**Source object:** [[01 ATT&CK/S1065 - Woody RAT|S1065: Woody RAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Woody RAT](https://attack.mitre.org/software/S1065) can collect information from a compromised host.(Citation: MalwareBytes WoodyRAT Aug 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--71bc9a2e-4536-4b84-9997-126cc4c065bf`.
