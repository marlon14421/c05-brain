---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0275"
target_object: "T1082"
stix_relationship_id: "relationship--90355089-e793-4a6a-98b4-c1f20322a98f"
---
# Relationship 3103: S0275 — uses → T1082

**Source object:** [[01 ATT&CK/S0275 - UPPERCUT|S0275: UPPERCUT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[UPPERCUT](https://attack.mitre.org/software/S0275) has the capability to gather the system’s hostname and OS version.(Citation: FireEye APT10 Sept 2018)(Citation: Trend Micro Earth Kasha Anel NOV 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--90355089-e793-4a6a-98b4-c1f20322a98f`.
