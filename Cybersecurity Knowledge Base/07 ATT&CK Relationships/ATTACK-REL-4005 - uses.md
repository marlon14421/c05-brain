---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0444"
target_object: "T1546.011"
stix_relationship_id: "relationship--9ec20e7b-8996-4f16-b830-1f8a0e99b778"
---
# Relationship 4005: S0444 — uses → T1546.011

**Source object:** [[01 ATT&CK/S0444 - ShimRat|S0444: ShimRat]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1546.011 - Application Shimming|T1546.011: Application Shimming]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ShimRat](https://attack.mitre.org/software/S0444) has installed shim databases in the AppPatch folder.(Citation: FOX-IT May 2016 Mofang)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9ec20e7b-8996-4f16-b830-1f8a0e99b778`.
