---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0069"
target_object: "S9032"
stix_relationship_id: "relationship--0ac9555c-10d1-450e-ba4e-6dd89a6a0624"
---
# Relationship 5877: G0069 — uses → S9032

**Source object:** [[01 ATT&CK/G0069 - MuddyWater|G0069: MuddyWater]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S9032 - MuddyViper|S9032: MuddyViper]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MuddyWater](https://attack.mitre.org/groups/G0069) has used [MuddyViper](https://attack.mitre.org/software/S9032) during operations.(Citation: ESET_MuddyWater_Dec2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0ac9555c-10d1-450e-ba4e-6dd89a6a0624`.
