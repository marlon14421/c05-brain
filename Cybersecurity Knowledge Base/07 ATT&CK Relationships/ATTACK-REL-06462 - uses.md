---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0526"
target_object: "T1680"
stix_relationship_id: "relationship--dd67596a-64c6-4dfb-b498-e7d5c1886090"
---
# Relationship 6462: S0526 — uses → T1680

**Source object:** [[01 ATT&CK/S0526 - KGH_SPY|S0526: KGH_SPY]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1680 - Local Storage Discovery|T1680: Local Storage Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[KGH_SPY](https://attack.mitre.org/software/S0526) can collect drive information from a compromised host.(Citation: Cybereason Kimsuky November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dd67596a-64c6-4dfb-b498-e7d5c1886090`.
