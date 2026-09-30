---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0409"
target_object: "T1217"
stix_relationship_id: "relationship--334ae43c-2c0b-4a7a-aab5-6ff59005dbf5"
---
# Relationship 6154: S0409 — uses → T1217

**Source object:** [[01 ATT&CK/S0409 - Machete|S0409: Machete]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1217 - Browser Information Discovery|T1217: Browser Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Machete](https://attack.mitre.org/software/S0409) retrieves the user profile data (e.g., browsers) from Chrome and Firefox browsers.(Citation: ESET Machete July 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--334ae43c-2c0b-4a7a-aab5-6ff59005dbf5`.
