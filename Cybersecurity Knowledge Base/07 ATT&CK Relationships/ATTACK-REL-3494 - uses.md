---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0143"
target_object: "T1218.011"
stix_relationship_id: "relationship--ced15447-281b-4d92-941e-b5df9747a3d5"
---
# Relationship 3494: S0143 — uses → T1218.011

**Source object:** [[01 ATT&CK/S0143 - Flame|S0143: Flame]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.011 - Rundll32|T1218.011: Rundll32]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

Rundll32.exe is used as a way of executing [Flame](https://attack.mitre.org/software/S0143) at the command-line.(Citation: Crysys Skywiper)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ced15447-281b-4d92-941e-b5df9747a3d5`.
