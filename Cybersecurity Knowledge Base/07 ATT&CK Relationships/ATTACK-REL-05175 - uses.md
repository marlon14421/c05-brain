---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1122"
target_object: "T1614.001"
stix_relationship_id: "relationship--29639eea-ddaf-44ce-95d3-053ba8a9eeb9"
---
# Relationship 5175: S1122 — uses → T1614.001

**Source object:** [[01 ATT&CK/S1122 - Mispadu|S1122: Mispadu]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1614.001 - System Language Discovery|T1614.001: System Language Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mispadu](https://attack.mitre.org/software/S1122) checks and will terminate execution if the compromised system’s language ID is not Spanish or Portuguese.(Citation: Segurança Informática URSA Sophisticated Loader 2020)(Citation: SCILabs Malteiro 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--29639eea-ddaf-44ce-95d3-053ba8a9eeb9`.
