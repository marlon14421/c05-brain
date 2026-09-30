---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0277"
target_object: "T1057"
stix_relationship_id: "relationship--112fec98-96be-4843-a56e-90d6b3fc02b2"
---
# Relationship 9128: S0277 — uses → T1057

**Source object:** [[01 ATT&CK/S0277 - FruitFly|S0277: FruitFly]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FruitFly](https://attack.mitre.org/software/S0277) has the ability to list processes on the system.(Citation: objsee mac malware 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--112fec98-96be-4843-a56e-90d6b3fc02b2`.
