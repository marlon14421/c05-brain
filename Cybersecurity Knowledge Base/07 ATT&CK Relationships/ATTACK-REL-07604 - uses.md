---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0627"
target_object: "T1497.003"
stix_relationship_id: "relationship--2426fc7d-5d97-4563-9889-d079ed36b4cf"
---
# Relationship 7604: S0627 — uses → T1497.003

**Source object:** [[01 ATT&CK/S0627 - SodaMaster|S0627: SodaMaster]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497.003 - Time Based Checks|T1497.003: Time Based Checks]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SodaMaster](https://attack.mitre.org/software/S0627) has the ability to put itself to "sleep" for a specified time.(Citation: Securelist APT10 March 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2426fc7d-5d97-4563-9889-d079ed36b4cf`.
