---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0673"
target_object: "T1568.002"
stix_relationship_id: "relationship--6be9fb86-54b4-4979-95f8-c2a27cba785c"
---
# Relationship 5330: S0673 — uses → T1568.002

**Source object:** [[01 ATT&CK/S0673 - DarkWatchman|S0673: DarkWatchman]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1568.002 - Domain Generation Algorithms|T1568.002: Domain Generation Algorithms]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DarkWatchman](https://attack.mitre.org/software/S0673) has used a DGA to generate a domain name for C2.(Citation: Prevailion DarkWatchman 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6be9fb86-54b4-4979-95f8-c2a27cba785c`.
