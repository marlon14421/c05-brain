---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0223"
target_object: "T1036.004"
stix_relationship_id: "relationship--2ccf654b-1077-4277-9a24-099fb3bf095f"
---
# Relationship 6802: S0223 — uses → T1036.004

**Source object:** [[01 ATT&CK/S0223 - POWERSTATS|S0223: POWERSTATS]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.004 - Masquerade Task or Service|T1036.004: Masquerade Task or Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[POWERSTATS](https://attack.mitre.org/software/S0223) has created a scheduled task named "MicrosoftEdge" to establish persistence.(Citation: ClearSky MuddyWater Nov 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2ccf654b-1077-4277-9a24-099fb3bf095f`.
