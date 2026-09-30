---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9036"
target_object: "T1078"
stix_relationship_id: "relationship--34bd47fc-20f7-487f-a5af-9cd60cdd3428"
---
# Relationship 6438: S9036 — uses → T1078

**Source object:** [[01 ATT&CK/S9036 - LP-Notes|S9036: LP-Notes]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1078 - Valid Accounts|T1078: Valid Accounts]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LP-Notes](https://attack.mitre.org/software/S9036) has used stolen Windows credentials to log in as the users.(Citation: ESET_MuddyWater_Dec2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--34bd47fc-20f7-487f-a5af-9cd60cdd3428`.
