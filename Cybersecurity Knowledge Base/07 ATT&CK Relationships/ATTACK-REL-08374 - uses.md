---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0182"
target_object: "T1027.002"
stix_relationship_id: "relationship--4636d747-9b81-4139-b86d-6e4edbc4111e"
---
# Relationship 8374: S0182 — uses → T1027.002

**Source object:** [[01 ATT&CK/S0182 - FinFisher|S0182: FinFisher]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.002 - Software Packing|T1027.002: Software Packing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

A [FinFisher](https://attack.mitre.org/software/S0182) variant uses a custom packer.(Citation: FinFisher Citation)(Citation: Securelist BlackOasis Oct 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4636d747-9b81-4139-b86d-6e4edbc4111e`.
