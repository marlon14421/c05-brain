---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0543"
target_object: "T1027.002"
stix_relationship_id: "relationship--25df53ed-4a07-4e71-8a1b-a84a2571e043"
---
# Relationship 7595: S0543 — uses → T1027.002

**Source object:** [[01 ATT&CK/S0543 - Spark|S0543: Spark]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.002 - Software Packing|T1027.002: Software Packing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Spark](https://attack.mitre.org/software/S0543) has been packed with Enigma Protector to obfuscate its contents.(Citation: Unit42 Molerat Mar 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--25df53ed-4a07-4e71-8a1b-a84a2571e043`.
