---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0016"
target_object: "T1621"
stix_relationship_id: "relationship--0cb7daf3-9c55-4210-a2a8-c5e40cf4ffbd"
---
# Relationship 5673: G0016 — uses → T1621

**Source object:** [[01 ATT&CK/G0016 - APT29|G0016: APT29]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1621 - Multi-Factor Authentication Request Generation|T1621: Multi-Factor Authentication Request Generation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT29](https://attack.mitre.org/groups/G0016) has used repeated MFA requests to gain access to victim accounts.(Citation: Suspected Russian Activity Targeting Government and Business Entities Around the Globe)(Citation: NCSC et al APT29 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0cb7daf3-9c55-4210-a2a8-c5e40cf4ffbd`.
