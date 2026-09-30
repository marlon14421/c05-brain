---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0543"
target_object: "T1497.002"
stix_relationship_id: "relationship--883a60f7-0111-4542-b590-2f0140ba26bd"
---
# Relationship 8743: S0543 — uses → T1497.002

**Source object:** [[01 ATT&CK/S0543 - Spark|S0543: Spark]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497.002 - User Activity Based Checks|T1497.002: User Activity Based Checks]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Spark](https://attack.mitre.org/software/S0543) has used a splash screen to check whether an user actively clicks on the screen before running malicious code.(Citation: Unit42 Molerat Mar 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--883a60f7-0111-4542-b590-2f0140ba26bd`.
