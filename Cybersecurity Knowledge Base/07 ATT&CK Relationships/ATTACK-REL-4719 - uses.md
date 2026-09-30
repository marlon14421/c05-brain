---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0113"
target_object: "T1025"
stix_relationship_id: "relationship--96e928af-dbfc-4743-a1dc-353904e21fd3"
---
# Relationship 4719: S0113 — uses → T1025

**Source object:** [[01 ATT&CK/S0113 - Prikormka|S0113: Prikormka]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1025 - Data from Removable Media|T1025: Data from Removable Media]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Prikormka](https://attack.mitre.org/software/S0113) contains a module that collects documents with certain extensions from removable media or fixed drives connected via USB.(Citation: ESET Operation Groundbait)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--96e928af-dbfc-4743-a1dc-353904e21fd3`.
