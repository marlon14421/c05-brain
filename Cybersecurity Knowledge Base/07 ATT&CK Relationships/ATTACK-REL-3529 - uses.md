---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0039"
target_object: "T1007"
stix_relationship_id: "relationship--1d36c3e8-238f-46c6-9b20-9fb4cb5c75ba"
---
# Relationship 3529: S0039 — uses → T1007

**Source object:** [[01 ATT&CK/S0039 - Net|S0039: Net]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1007 - System Service Discovery|T1007: System Service Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

The net start command can be used in [Net](https://attack.mitre.org/software/S0039) to find information about Windows services.(Citation: Savill 1999)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1d36c3e8-238f-46c6-9b20-9fb4cb5c75ba`.
