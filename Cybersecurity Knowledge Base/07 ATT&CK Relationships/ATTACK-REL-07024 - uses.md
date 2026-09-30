---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0143"
target_object: "S0430"
stix_relationship_id: "relationship--f5d63c0b-0857-4382-9f45-c45beba57737"
---
# Relationship 7024: G0143 — uses → S0430

**Source object:** [[01 ATT&CK/G0143 - Aquatic Panda|G0143: Aquatic Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0430 - Winnti for Linux|S0430: Winnti for Linux]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Aquatic Panda](https://attack.mitre.org/groups/G0143) used [Winnti for Linux](https://attack.mitre.org/software/S0430) for access to victim Linux hosts during intrusions(Citation: Crowdstrike HuntReport 2022).

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f5d63c0b-0857-4382-9f45-c45beba57737`.
