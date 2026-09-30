---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0569"
target_object: "T1016"
stix_relationship_id: "relationship--00038d0e-7fc7-41c3-9055-edb4d87ea912"
---
# Relationship 5456: S0569 — uses → T1016

**Source object:** [[01 ATT&CK/S0569 - Explosive|S0569: Explosive]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Explosive](https://attack.mitre.org/software/S0569) has collected the MAC address from the victim's machine.(Citation: CheckPoint Volatile Cedar March 2015)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--00038d0e-7fc7-41c3-9055-edb4d87ea912`.
