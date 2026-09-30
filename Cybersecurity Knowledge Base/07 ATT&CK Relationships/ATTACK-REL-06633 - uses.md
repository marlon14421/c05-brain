---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1019"
target_object: "T1071.004"
stix_relationship_id: "relationship--e9113d90-4c55-465a-88c6-b58c40b46f96"
---
# Relationship 6633: S1019 — uses → T1071.004

**Source object:** [[01 ATT&CK/S1019 - Shark|S1019: Shark]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.004 - DNS|T1071.004: DNS]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Shark](https://attack.mitre.org/software/S1019) can use DNS in C2 communications.(Citation: ClearSky Siamesekitten August 2021)(Citation: Accenture Lyceum Targets November 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e9113d90-4c55-465a-88c6-b58c40b46f96`.
