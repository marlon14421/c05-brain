---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1068"
target_object: "T1033"
stix_relationship_id: "relationship--f8c2b8e1-7439-48df-a8c3-6796fd4bb142"
---
# Relationship 3600: S1068 — uses → T1033

**Source object:** [[01 ATT&CK/S1068 - BlackCat|S1068: BlackCat]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BlackCat](https://attack.mitre.org/software/S1068) can utilize `net use` commands to discover the user name on a compromised host.(Citation: Microsoft BlackCat Jun 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f8c2b8e1-7439-48df-a8c3-6796fd4bb142`.
