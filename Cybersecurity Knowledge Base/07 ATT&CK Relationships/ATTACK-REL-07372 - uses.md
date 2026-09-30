---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0496"
target_object: "T1485"
stix_relationship_id: "relationship--31bf8ae4-e757-462c-aa30-c4a9dd92c677"
---
# Relationship 7372: S0496 — uses → T1485

**Source object:** [[01 ATT&CK/S0496 - REvil|S0496: REvil]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1485 - Data Destruction|T1485: Data Destruction]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[REvil](https://attack.mitre.org/software/S0496) has the capability to destroy files and folders.(Citation: Kaspersky Sodin July 2019)(Citation: Secureworks GandCrab and REvil September 2019)(Citation: McAfee Sodinokibi October 2019)(Citation: McAfee Sodinokibi October 2019)(Citation: Intel 471 REvil March 2020)(Citation: Picus Sodinokibi January 2020)(Citation: Secureworks REvil September 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--31bf8ae4-e757-462c-aa30-c4a9dd92c677`.
