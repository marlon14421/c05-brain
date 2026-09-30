---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0531"
target_object: "T1102.001"
stix_relationship_id: "relationship--2ad63ab0-fb5b-4bce-8bbb-bf765d324fd6"
---
# Relationship 7765: S0531 — uses → T1102.001

**Source object:** [[01 ATT&CK/S0531 - Grandoreiro|S0531: Grandoreiro]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102.001 - Dead Drop Resolver|T1102.001: Dead Drop Resolver]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Grandoreiro](https://attack.mitre.org/software/S0531) can obtain C2 information from Google Docs.(Citation: Securelist Brazilian Banking Malware July 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2ad63ab0-fb5b-4bce-8bbb-bf765d324fd6`.
