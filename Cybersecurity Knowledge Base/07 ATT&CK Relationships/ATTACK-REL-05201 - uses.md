---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0579"
target_object: "T1027.005"
stix_relationship_id: "relationship--e041070a-ff38-47ee-aebd-8d1bc714231e"
---
# Relationship 5201: S0579 — uses → T1027.005

**Source object:** [[01 ATT&CK/S0579 - Waterbear|S0579: Waterbear]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.005 - Indicator Removal from Tools|T1027.005: Indicator Removal from Tools]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Waterbear](https://attack.mitre.org/software/S0579) can scramble functions not to be executed again with random values.(Citation: Trend Micro Waterbear December 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e041070a-ff38-47ee-aebd-8d1bc714231e`.
