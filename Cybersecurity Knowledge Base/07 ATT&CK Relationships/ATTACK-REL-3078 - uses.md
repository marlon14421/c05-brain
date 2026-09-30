---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0237"
target_object: "T1007"
stix_relationship_id: "relationship--948f8c8b-18e1-4652-86af-bad1dc0ec090"
---
# Relationship 3078: S0237 — uses → T1007

**Source object:** [[01 ATT&CK/S0237 - GravityRAT|S0237: GravityRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1007 - System Service Discovery|T1007: System Service Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[GravityRAT](https://attack.mitre.org/software/S0237) has a feature to list the available services on the system.(Citation: Talos GravityRAT)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--948f8c8b-18e1-4652-86af-bad1dc0ec090`.
