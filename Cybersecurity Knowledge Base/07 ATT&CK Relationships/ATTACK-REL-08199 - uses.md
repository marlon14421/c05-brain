---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0484"
target_object: "T1497"
stix_relationship_id: "relationship--2c112e41-be75-4f99-84ac-ce7776f88fca"
---
# Relationship 8199: S0484 — uses → T1497

**Source object:** [[01 ATT&CK/S0484 - Carberp|S0484: Carberp]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497 - Virtualization-Sandbox Evasion|T1497: Virtualization/Sandbox Evasion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Carberp](https://attack.mitre.org/software/S0484) has removed various hooks before installing the trojan or bootkit to evade sandbox analysis or other analysis software.(Citation: ESET Carberp March 2012)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2c112e41-be75-4f99-84ac-ce7776f88fca`.
