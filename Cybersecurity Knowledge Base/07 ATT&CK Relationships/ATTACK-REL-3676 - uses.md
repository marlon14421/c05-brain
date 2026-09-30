---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9001"
target_object: "T1053.005"
stix_relationship_id: "relationship--02085573-6f4a-495f-b3a7-81ac97ce3377"
---
# Relationship 3676: S9001 — uses → T1053.005

**Source object:** [[01 ATT&CK/S9001 - SystemBC|S9001: SystemBC]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SystemBC](https://attack.mitre.org/software/S9001) has executed a copy of itself as a scheduled task with the `start` command. The copy of [SystemBC](https://attack.mitre.org/software/S9001) has random file and directory names within the ProgramData directory.(Citation: SophosGnGal_SystemBC_Dec2020)(Citation: TrumanKroll_SYSTEMBCServer_Jan2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--02085573-6f4a-495f-b3a7-81ac97ce3377`.
