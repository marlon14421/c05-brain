---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0260"
target_object: "T1055.002"
stix_relationship_id: "relationship--0ed82dd2-9b78-49a7-990b-d59ad7fa40a1"
---
# Relationship 5021: S0260 — uses → T1055.002

**Source object:** [[01 ATT&CK/S0260 - InvisiMole|S0260: InvisiMole]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.002 - Portable Executable Injection|T1055.002: Portable Executable Injection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[InvisiMole](https://attack.mitre.org/software/S0260) can inject its backdoor as a portable executable into a target process.(Citation: ESET InvisiMole June 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0ed82dd2-9b78-49a7-990b-d59ad7fa40a1`.
