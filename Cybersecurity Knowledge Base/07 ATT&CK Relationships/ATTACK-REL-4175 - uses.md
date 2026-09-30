---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0444"
target_object: "T1106"
stix_relationship_id: "relationship--bdd7c955-c41a-4b68-9eb6-1ecd66869457"
---
# Relationship 4175: S0444 — uses → T1106

**Source object:** [[01 ATT&CK/S0444 - ShimRat|S0444: ShimRat]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ShimRat](https://attack.mitre.org/software/S0444) has used Windows API functions to install the service and shim.(Citation: FOX-IT May 2016 Mofang)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bdd7c955-c41a-4b68-9eb6-1ecd66869457`.
