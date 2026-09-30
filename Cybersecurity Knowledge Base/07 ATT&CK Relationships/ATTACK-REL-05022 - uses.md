---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0027"
target_object: "T1210"
stix_relationship_id: "relationship--f9ec1b10-f819-42d8-a4b4-ecf015999cb6"
---
# Relationship 5022: G0027 — uses → T1210

**Source object:** [[01 ATT&CK/G0027 - Threat Group-3390|G0027: Threat Group-3390]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1210 - Exploitation of Remote Services|T1210: Exploitation of Remote Services]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Threat Group-3390](https://attack.mitre.org/groups/G0027) has exploited MS17-010 to move laterally to other systems on the network.(Citation: Unit42 Emissary Panda May 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f9ec1b10-f819-42d8-a4b4-ecf015999cb6`.
