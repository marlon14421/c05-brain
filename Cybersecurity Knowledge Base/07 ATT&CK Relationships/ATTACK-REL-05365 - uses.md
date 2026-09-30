---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0684"
target_object: "T1526"
stix_relationship_id: "relationship--3c9a5581-9199-4612-8840-06844b23cd1d"
---
# Relationship 5365: S0684 — uses → T1526

**Source object:** [[01 ATT&CK/S0684 - ROADTools|S0684: ROADTools]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1526 - Cloud Service Discovery|T1526: Cloud Service Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ROADTools](https://attack.mitre.org/software/S0684) can enumerate Azure AD applications and service principals.(Citation: Roadtools)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3c9a5581-9199-4612-8840-06844b23cd1d`.
