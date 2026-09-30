---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0348"
target_object: "T1027.004"
stix_relationship_id: "relationship--94bb62b3-e917-47cb-a717-560b28ea3d56"
---
# Relationship 9883: S0348 — uses → T1027.004

**Source object:** [[01 ATT&CK/S0348 - Cardinal RAT|S0348: Cardinal RAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.004 - Compile After Delivery|T1027.004: Compile After Delivery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Cardinal RAT](https://attack.mitre.org/software/S0348) and its watchdog component are compiled and executed after being delivered to victims as embedded, uncompiled source code.(Citation: PaloAlto CardinalRat Apr 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--94bb62b3-e917-47cb-a717-560b28ea3d56`.
