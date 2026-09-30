---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1040"
target_object: "T1003.001"
stix_relationship_id: "relationship--f061c68a-7a2f-4cad-af24-9dc55415f956"
---
# Relationship 4420: G1040 — uses → T1003.001

**Source object:** [[01 ATT&CK/G1040 - Play|G1040: Play]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003.001 - LSASS Memory|T1003.001: LSASS Memory]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Play](https://attack.mitre.org/groups/G1040) has used [Mimikatz](https://attack.mitre.org/software/S0002) and the Windows Task Manager to dump LSASS process memory.(Citation: Trend Micro Ransomware Spotlight Play July 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f061c68a-7a2f-4cad-af24-9dc55415f956`.
