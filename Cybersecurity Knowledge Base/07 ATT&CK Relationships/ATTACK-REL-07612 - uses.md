---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1034"
target_object: "T1497.003"
stix_relationship_id: "relationship--8aeea825-de75-404b-bde3-806ba749f416"
---
# Relationship 7612: S1034 — uses → T1497.003

**Source object:** [[01 ATT&CK/S1034 - StrifeWater|S1034: StrifeWater]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497.003 - Time Based Checks|T1497.003: Time Based Checks]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[StrifeWater](https://attack.mitre.org/software/S1034) can modify its sleep time responses from the default of 20-22 seconds.(Citation: Cybereason StrifeWater Feb 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8aeea825-de75-404b-bde3-806ba749f416`.
