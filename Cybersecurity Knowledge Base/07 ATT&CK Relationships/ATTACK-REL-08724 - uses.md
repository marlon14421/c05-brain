---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0538"
target_object: "T1119"
stix_relationship_id: "relationship--c9e82790-f096-46f0-ba55-579d77ec3ea8"
---
# Relationship 8724: S0538 — uses → T1119

**Source object:** [[01 ATT&CK/S0538 - Crutch|S0538: Crutch]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1119 - Automated Collection|T1119: Automated Collection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Crutch](https://attack.mitre.org/software/S0538) can automatically monitor removable drives in a loop and copy interesting files.(Citation: ESET Crutch December 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c9e82790-f096-46f0-ba55-579d77ec3ea8`.
