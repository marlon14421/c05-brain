---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0032"
target_object: "T1564.001"
stix_relationship_id: "relationship--2426519f-c915-4c8f-8164-0d93dbbf0be1"
---
# Relationship 3416: G0032 — uses → T1564.001

**Source object:** [[01 ATT&CK/G0032 - Lazarus Group|G0032: Lazarus Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.001 - Hidden Files and Directories|T1564.001: Hidden Files and Directories]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Lazarus Group](https://attack.mitre.org/groups/G0032) has used a VBA Macro to set its file attributes to System and Hidden and has named files with a dot prefix to hide them from the Finder application.(Citation: McAfee Lazarus Resurfaces Feb 2018)(Citation: SentinelOne Lazarus macOS July 2020)(Citation: TrendMicro macOS Dacls May 2020)(Citation: Lazarus APT January 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2426519f-c915-4c8f-8164-0d93dbbf0be1`.
