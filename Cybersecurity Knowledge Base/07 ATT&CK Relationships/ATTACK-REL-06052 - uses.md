---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0255"
target_object: "T1218.011"
stix_relationship_id: "relationship--592324b4-064a-430c-8ffc-7f7acd537778"
---
# Relationship 6052: S0255 — uses → T1218.011

**Source object:** [[01 ATT&CK/S0255 - DDKONG|S0255: DDKONG]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.011 - Rundll32|T1218.011: Rundll32]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DDKONG](https://attack.mitre.org/software/S0255) uses Rundll32 to ensure only a single instance of itself is running at once.(Citation: Rancor Unit42 June 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--592324b4-064a-430c-8ffc-7f7acd537778`.
