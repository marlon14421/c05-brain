---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0352"
target_object: "T1070.004"
stix_relationship_id: "relationship--207c59d5-9df0-4838-9a0a-5555ea78b35f"
---
# Relationship 3356: S0352 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0352 - OSX_OCEANLOTUS.D|S0352: OSX_OCEANLOTUS.D]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[OSX_OCEANLOTUS.D](https://attack.mitre.org/software/S0352) has a command to delete a file from the system. [OSX_OCEANLOTUS.D](https://attack.mitre.org/software/S0352) deletes the app bundle and dropper after execution.(Citation: TrendMicro MacOS April 2018)(Citation: Trend Micro MacOS Backdoor November 2020)(Citation: Unit42 OceanLotus 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--207c59d5-9df0-4838-9a0a-5555ea78b35f`.
