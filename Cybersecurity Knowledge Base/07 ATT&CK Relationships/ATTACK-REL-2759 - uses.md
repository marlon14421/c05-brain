---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0258"
target_object: "T1033"
stix_relationship_id: "relationship--ada55a0e-2f38-4da1-9ebd-8dd2f2461dfc"
---
# Relationship 2759: S0258 — uses → T1033

**Source object:** [[01 ATT&CK/S0258 - RGDoor|S0258: RGDoor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[RGDoor](https://attack.mitre.org/software/S0258) executes the whoami on the victim’s machine.(Citation: Unit 42 RGDoor Jan 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ada55a0e-2f38-4da1-9ebd-8dd2f2461dfc`.
