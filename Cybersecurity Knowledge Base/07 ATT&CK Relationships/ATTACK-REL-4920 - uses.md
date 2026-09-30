---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0089"
target_object: "T1685.005"
stix_relationship_id: "relationship--201a9d42-beef-4cab-866a-0e045d83eb21"
---
# Relationship 4920: S0089 — uses → T1685.005

**Source object:** [[01 ATT&CK/S0089 - BlackEnergy|S0089: BlackEnergy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1685.005 - Clear Windows Event Logs|T1685.005: Clear Windows Event Logs]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

The [BlackEnergy](https://attack.mitre.org/software/S0089) component KillDisk is capable of deleting Windows Event Logs.(Citation: ESEST Black Energy Jan 2016)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--201a9d42-beef-4cab-866a-0e045d83eb21`.
