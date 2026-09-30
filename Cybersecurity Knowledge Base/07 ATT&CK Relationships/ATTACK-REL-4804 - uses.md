---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0149"
target_object: "T1074.001"
stix_relationship_id: "relationship--9c4a8336-5f5f-4e58-b00d-b6bf1c59ec03"
---
# Relationship 4804: S0149 — uses → T1074.001

**Source object:** [[01 ATT&CK/S0149 - MoonWind|S0149: MoonWind]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1074.001 - Local Data Staging|T1074.001: Local Data Staging]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[MoonWind](https://attack.mitre.org/software/S0149) saves information from its keylogging routine as a .zip file in the present working directory.(Citation: Palo Alto MoonWind March 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9c4a8336-5f5f-4e58-b00d-b6bf1c59ec03`.
