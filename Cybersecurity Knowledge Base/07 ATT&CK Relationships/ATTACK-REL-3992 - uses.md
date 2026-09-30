---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0603"
target_object: "T1008"
stix_relationship_id: "relationship--85b5e45d-247e-4c8b-a991-95700e4d81d9"
---
# Relationship 3992: S0603 — uses → T1008

**Source object:** [[01 ATT&CK/S0603 - Stuxnet|S0603: Stuxnet]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1008 - Fallback Channels|T1008: Fallback Channels]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Stuxnet](https://attack.mitre.org/software/S0603) has the ability to generate new C2 domains.(Citation: Nicolas Falliere, Liam O Murchu, Eric Chien February 2011)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--85b5e45d-247e-4c8b-a991-95700e4d81d9`.
