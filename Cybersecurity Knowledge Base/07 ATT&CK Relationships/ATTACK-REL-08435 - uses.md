---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0182"
target_object: "T1497.001"
stix_relationship_id: "relationship--2af8a4f4-fcac-4081-86f9-ba74140580dc"
---
# Relationship 8435: S0182 — uses → T1497.001

**Source object:** [[01 ATT&CK/S0182 - FinFisher|S0182: FinFisher]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497.001 - System Checks|T1497.001: System Checks]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FinFisher](https://attack.mitre.org/software/S0182) obtains the hardware device list and checks if the MD5 of the vendor ID is equal to a predefined list in order to check for sandbox/virtualized environments.(Citation: Microsoft FinFisher March 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2af8a4f4-fcac-4081-86f9-ba74140580dc`.
