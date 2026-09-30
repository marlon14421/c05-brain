---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0444"
target_object: "T1059.003"
stix_relationship_id: "relationship--84d3fa4b-a4c6-404c-a363-0d9a96381952"
---
# Relationship 6416: S0444 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0444 - ShimRat|S0444: ShimRat]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ShimRat](https://attack.mitre.org/software/S0444) can be issued a command shell function from the C2.(Citation: FOX-IT May 2016 Mofang)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--84d3fa4b-a4c6-404c-a363-0d9a96381952`.
