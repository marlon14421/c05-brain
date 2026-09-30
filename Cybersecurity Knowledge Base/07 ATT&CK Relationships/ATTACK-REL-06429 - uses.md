---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0622"
target_object: "T1025"
stix_relationship_id: "relationship--e465cb38-ba50-4d2d-b2cd-659742815317"
---
# Relationship 6429: S0622 — uses → T1025

**Source object:** [[01 ATT&CK/S0622 - AppleSeed|S0622: AppleSeed]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1025 - Data from Removable Media|T1025: Data from Removable Media]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[AppleSeed](https://attack.mitre.org/software/S0622) can find and collect data from removable media devices.(Citation: Malwarebytes Kimsuky June 2021)(Citation: KISA Operation Muzabi)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e465cb38-ba50-4d2d-b2cd-659742815317`.
