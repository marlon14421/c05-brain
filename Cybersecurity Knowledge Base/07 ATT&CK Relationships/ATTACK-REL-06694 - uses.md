---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0270"
target_object: "T1113"
stix_relationship_id: "relationship--e769177d-17b8-443b-b939-206d724fbb40"
---
# Relationship 6694: S0270 — uses → T1113

**Source object:** [[01 ATT&CK/S0270 - RogueRobin|S0270: RogueRobin]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RogueRobin](https://attack.mitre.org/software/S0270) has a command named $screenshot that may be responsible for taking screenshots of the victim machine.(Citation: Unit 42 DarkHydrus July 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e769177d-17b8-443b-b939-206d724fbb40`.
