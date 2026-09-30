---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0552"
target_object: "T1087.002"
stix_relationship_id: "relationship--fb21ff9d-1cd5-4908-a3a4-5f0d22cb8c10"
---
# Relationship 5904: S0552 — uses → T1087.002

**Source object:** [[01 ATT&CK/S0552 - AdFind|S0552: AdFind]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1087.002 - Domain Account|T1087.002: Domain Account]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[AdFind](https://attack.mitre.org/software/S0552) can enumerate domain users.(Citation: Red Canary Hospital Thwarted Ryuk October 2020)(Citation: FireEye FIN6 Apr 2019)(Citation: FireEye Ryuk and Trickbot January 2019)(Citation: Cybereason Bumblebee August 2022)(Citation: Symantec Bumblebee June 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fb21ff9d-1cd5-4908-a3a4-5f0d22cb8c10`.
