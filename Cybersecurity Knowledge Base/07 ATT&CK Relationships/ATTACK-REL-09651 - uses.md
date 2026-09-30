---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0409"
target_object: "T1113"
stix_relationship_id: "relationship--fb99048f-bb37-47be-b2a5-d03d9ff087f1"
---
# Relationship 9651: S0409 — uses → T1113

**Source object:** [[01 ATT&CK/S0409 - Machete|S0409: Machete]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Machete](https://attack.mitre.org/software/S0409) captures screenshots.(Citation: ESET Machete July 2019)(Citation: Securelist Machete Aug 2014)(Citation: Cylance Machete Mar 2017)(Citation: 360 Machete Sep 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fb99048f-bb37-47be-b2a5-d03d9ff087f1`.
