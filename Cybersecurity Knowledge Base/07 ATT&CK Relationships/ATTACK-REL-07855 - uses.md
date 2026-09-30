---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0039"
target_object: "T1087.001"
stix_relationship_id: "relationship--15f74597-d92d-406f-9941-c0dfef3cb609"
---
# Relationship 7855: S0039 — uses → T1087.001

**Source object:** [[01 ATT&CK/S0039 - Net|S0039: Net]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1087.001 - Local Account|T1087.001: Local Account]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Commands under net user can be used in [Net](https://attack.mitre.org/software/S0039) to gather information about and manipulate user accounts.(Citation: Savill 1999)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--15f74597-d92d-406f-9941-c0dfef3cb609`.
