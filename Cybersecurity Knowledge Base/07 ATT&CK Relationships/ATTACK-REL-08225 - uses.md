---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0674"
target_object: "T1016"
stix_relationship_id: "relationship--c7ef866c-18f8-485e-99d2-78b7e48576d8"
---
# Relationship 8225: S0674 — uses → T1016

**Source object:** [[01 ATT&CK/S0674 - CharmPower|S0674: CharmPower]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CharmPower](https://attack.mitre.org/software/S0674) has the ability to use ipconfig to enumerate system network settings.(Citation: Check Point APT35 CharmPower January 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c7ef866c-18f8-485e-99d2-78b7e48576d8`.
