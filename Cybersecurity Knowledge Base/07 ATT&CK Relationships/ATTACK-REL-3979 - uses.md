---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0441"
target_object: "T1016"
stix_relationship_id: "relationship--aaf0545f-bb47-4796-b23e-4780f354add9"
---
# Relationship 3979: S0441 — uses → T1016

**Source object:** [[01 ATT&CK/S0441 - PowerShower|S0441: PowerShower]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PowerShower](https://attack.mitre.org/software/S0441) has the ability to identify the current Windows domain of the infected host.(Citation: Kaspersky Cloud Atlas August 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--aaf0545f-bb47-4796-b23e-4780f354add9`.
