---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1125"
target_object: "T1485"
stix_relationship_id: "relationship--28d36206-062f-42be-93a1-f9cf2910c3c4"
---
# Relationship 6420: S1125 — uses → T1485

**Source object:** [[01 ATT&CK/S1125 - AcidRain|S1125: AcidRain]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1485 - Data Destruction|T1485: Data Destruction]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[AcidRain](https://attack.mitre.org/software/S1125) performs an in-depth wipe of the target filesystem and various attached storage devices through either a data overwrite or calling various IOCTLS to erase it.(Citation: AcidRain JAGS 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--28d36206-062f-42be-93a1-f9cf2910c3c4`.
