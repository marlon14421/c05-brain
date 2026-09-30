---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0649"
target_object: "T1082"
stix_relationship_id: "relationship--4ae0fc35-a321-4ffb-b7fa-b03a20230fc4"
---
# Relationship 7435: S0649 — uses → T1082

**Source object:** [[01 ATT&CK/S0649 - SMOKEDHAM|S0649: SMOKEDHAM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SMOKEDHAM](https://attack.mitre.org/software/S0649) has used the systeminfo command on a compromised host.(Citation: FireEye SMOKEDHAM June 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4ae0fc35-a321-4ffb-b7fa-b03a20230fc4`.
