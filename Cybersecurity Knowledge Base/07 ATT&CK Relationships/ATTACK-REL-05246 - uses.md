---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0004"
target_object: "T1114.002"
stix_relationship_id: "relationship--021885d8-90a5-4d70-91de-869783cd57d3"
---
# Relationship 5246: G0004 — uses → T1114.002

**Source object:** [[01 ATT&CK/G0004 - Ke3chang|G0004: Ke3chang]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1114.002 - Remote Email Collection|T1114.002: Remote Email Collection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ke3chang](https://attack.mitre.org/groups/G0004) has used compromised credentials and a .NET tool to dump data from Microsoft Exchange mailboxes.(Citation: NCC Group APT15 Alive and Strong)(Citation: Microsoft NICKEL December 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--021885d8-90a5-4d70-91de-869783cd57d3`.
