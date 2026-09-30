---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1222"
target_object: "T1074.001"
stix_relationship_id: "relationship--e43c3765-10e6-40f4-b318-39ee3f34819e"
---
# Relationship 2916: S1222 — uses → T1074.001

**Source object:** [[01 ATT&CK/S1222 - RIFLESPINE|S1222: RIFLESPINE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1074.001 - Local Data Staging|T1074.001: Local Data Staging]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[RIFLESPINE](https://attack.mitre.org/software/S1222) can stage the output from executed C2 commands to a temporary file.(Citation: Google Cloud Mandiant UNC3886 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e43c3765-10e6-40f4-b318-39ee3f34819e`.
