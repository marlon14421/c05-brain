---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0552"
target_object: "T1018"
stix_relationship_id: "relationship--dfe9acb4-48fe-4241-8b17-d76534f75b62"
---
# Relationship 7136: S0552 — uses → T1018

**Source object:** [[01 ATT&CK/S0552 - AdFind|S0552: AdFind]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1018 - Remote System Discovery|T1018: Remote System Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[AdFind](https://attack.mitre.org/software/S0552) has the ability to query Active Directory for computers.(Citation: Red Canary Hospital Thwarted Ryuk October 2020)(Citation: FireEye FIN6 Apr 2019)(Citation: FireEye Ryuk and Trickbot January 2019)(Citation: Cybereason Bumblebee August 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dfe9acb4-48fe-4241-8b17-d76534f75b62`.
