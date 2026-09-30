---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0125"
target_object: "T1078.003"
stix_relationship_id: "relationship--996765a6-6c8a-429d-baa5-32d423fb4207"
---
# Relationship 6356: G0125 — uses → T1078.003

**Source object:** [[01 ATT&CK/G0125 - HAFNIUM|G0125: HAFNIUM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1078.003 - Local Accounts|T1078.003: Local Accounts]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HAFNIUM](https://attack.mitre.org/groups/G0125) has used the NT AUTHORITY\SYSTEM account to create files on Exchange servers.(Citation: FireEye Exchange Zero Days March 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--996765a6-6c8a-429d-baa5-32d423fb4207`.
