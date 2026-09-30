---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0264"
target_object: "T1059.005"
stix_relationship_id: "relationship--acb06172-23a6-4190-a568-63da13491e6e"
---
# Relationship 6683: S0264 — uses → T1059.005

**Source object:** [[01 ATT&CK/S0264 - OopsIE|S0264: OopsIE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.005 - Visual Basic|T1059.005: Visual Basic]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[OopsIE](https://attack.mitre.org/software/S0264) creates and uses a VBScript as part of its persistent execution.(Citation: Unit 42 OopsIE! Feb 2018)(Citation: Unit 42 OilRig Sept 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--acb06172-23a6-4190-a568-63da13491e6e`.
