---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1133"
target_object: "T1685.005"
stix_relationship_id: "relationship--035ad845-9a13-41bb-b7c1-1bd47d787605"
---
# Relationship 2907: S1133 — uses → T1685.005

**Source object:** [[01 ATT&CK/S1133 - Apostle|S1133: Apostle]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1685.005 - Clear Windows Event Logs|T1685.005: Clear Windows Event Logs]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Apostle](https://attack.mitre.org/software/S1133) will attempt to delete all event logs on a victim machine following file wipe activity.(Citation: SentinelOne Agrius 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--035ad845-9a13-41bb-b7c1-1bd47d787605`.
