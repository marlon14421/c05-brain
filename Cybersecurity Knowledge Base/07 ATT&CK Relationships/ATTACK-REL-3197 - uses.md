---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0034"
target_object: "T1059.001"
stix_relationship_id: "relationship--1d8fedc7-e139-4806-9904-3cc2bf8b9334"
---
# Relationship 3197: G0034 — uses → T1059.001

**Source object:** [[01 ATT&CK/G0034 - Sandworm Team|G0034: Sandworm Team]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Sandworm Team](https://attack.mitre.org/groups/G0034) has used PowerShell scripts to run a credential harvesting tool in memory to evade defenses.(Citation: US District Court Indictment GRU Unit 74455 October 2020)(Citation: Dragos Crashoverride 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1d8fedc7-e139-4806-9904-3cc2bf8b9334`.
