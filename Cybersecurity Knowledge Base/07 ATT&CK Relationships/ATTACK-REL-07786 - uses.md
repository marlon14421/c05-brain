---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0336"
target_object: "T1059.005"
stix_relationship_id: "relationship--a01519cd-b198-4c60-a5ed-1ca3528d0606"
---
# Relationship 7786: S0336 — uses → T1059.005

**Source object:** [[01 ATT&CK/S0336 - NanoCore|S0336: NanoCore]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.005 - Visual Basic|T1059.005: Visual Basic]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[NanoCore](https://attack.mitre.org/software/S0336) uses VBS files.(Citation: Cofense NanoCore Mar 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a01519cd-b198-4c60-a5ed-1ca3528d0606`.
