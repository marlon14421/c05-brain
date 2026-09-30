---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0032"
target_object: "T1218.011"
stix_relationship_id: "relationship--5a771636-9b4d-423c-b7ba-1f274cbfb5b7"
---
# Relationship 6776: S0032 — uses → T1218.011

**Source object:** [[01 ATT&CK/S0032 - gh0st RAT|S0032: gh0st RAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.011 - Rundll32|T1218.011: Rundll32]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

A [gh0st RAT](https://attack.mitre.org/software/S0032) variant has used rundll32 for execution.(Citation: Arbor Musical Chairs Feb 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5a771636-9b4d-423c-b7ba-1f274cbfb5b7`.
