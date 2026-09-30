---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0492"
target_object: "T1059.004"
stix_relationship_id: "relationship--dcbe360b-c7d3-45bd-a1ef-a13bc2a562fe"
---
# Relationship 7072: S0492 — uses → T1059.004

**Source object:** [[01 ATT&CK/S0492 - CookieMiner|S0492: CookieMiner]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.004 - Unix Shell|T1059.004: Unix Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CookieMiner](https://attack.mitre.org/software/S0492) has used a Unix shell script to run a series of commands targeting macOS.(Citation: Unit42 CookieMiner Jan 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dcbe360b-c7d3-45bd-a1ef-a13bc2a562fe`.
