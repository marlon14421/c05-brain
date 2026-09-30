---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0260"
target_object: "T1005"
stix_relationship_id: "relationship--63738109-c04a-4af9-a671-636c493d7a21"
---
# Relationship 9013: S0260 — uses → T1005

**Source object:** [[01 ATT&CK/S0260 - InvisiMole|S0260: InvisiMole]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[InvisiMole](https://attack.mitre.org/software/S0260) can collect data from the system, and can monitor changes in specified directories.(Citation: ESET InvisiMole June 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--63738109-c04a-4af9-a671-636c493d7a21`.
