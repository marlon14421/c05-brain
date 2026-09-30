---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1023"
target_object: "T1005"
stix_relationship_id: "relationship--aef756f0-f34d-4cae-a16d-65e456f75c35"
---
# Relationship 4123: S1023 — uses → T1005

**Source object:** [[01 ATT&CK/S1023 - CreepyDrive|S1023: CreepyDrive]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[CreepyDrive](https://attack.mitre.org/software/S1023) can upload files to C2 from victim machines.(Citation: Microsoft POLONIUM June 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--aef756f0-f34d-4cae-a16d-65e456f75c35`.
