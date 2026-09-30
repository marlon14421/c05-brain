---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9001"
target_object: "T1095"
stix_relationship_id: "relationship--c8c8c0bc-0240-4cd1-aff3-edbe19a91e57"
---
# Relationship 9518: S9001 — uses → T1095

**Source object:** [[01 ATT&CK/S9001 - SystemBC|S9001: SystemBC]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1095 - Non-Application Layer Protocol|T1095: Non-Application Layer Protocol]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SystemBC](https://attack.mitre.org/software/S9001) has used raw TCP on non-standard ports, such as 4044, for C2 communications and for HTTP communications, which include downloading binaries.(Citation: SophosGnGal_SystemBC_Dec2020)(Citation: AhnLab_SystemBC_Apr2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c8c8c0bc-0240-4cd1-aff3-edbe19a91e57`.
