---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0346"
target_object: "T1057"
stix_relationship_id: "relationship--a3138e56-a496-486d-b11e-5e1c39a9c15d"
---
# Relationship 7206: S0346 — uses → T1057

**Source object:** [[01 ATT&CK/S0346 - OceanSalt|S0346: OceanSalt]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[OceanSalt](https://attack.mitre.org/software/S0346) can collect the name and ID for every process running on the system.(Citation: McAfee Oceansalt Oct 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a3138e56-a496-486d-b11e-5e1c39a9c15d`.
