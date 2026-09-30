---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0614"
target_object: "T1106"
stix_relationship_id: "relationship--f10beefd-2bc1-4657-9c55-0ee28905b9ac"
---
# Relationship 3137: S0614 — uses → T1106

**Source object:** [[01 ATT&CK/S0614 - CostaBricks|S0614: CostaBricks]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[CostaBricks](https://attack.mitre.org/software/S0614) has used a number of API calls, including `VirtualAlloc`, `VirtualFree`, `LoadLibraryA`, `GetProcAddress`, and `ExitProcess`.(Citation: BlackBerry CostaRicto November 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f10beefd-2bc1-4657-9c55-0ee28905b9ac`.
