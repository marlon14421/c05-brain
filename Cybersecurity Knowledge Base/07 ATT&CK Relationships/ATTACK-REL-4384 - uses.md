---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1152"
target_object: "T1564.003"
stix_relationship_id: "relationship--b5c99a08-a5ab-41fc-88fa-1f3d3f9da504"
---
# Relationship 4384: S1152 — uses → T1564.003

**Source object:** [[01 ATT&CK/S1152 - IMAPLoader|S1152: IMAPLoader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.003 - Hidden Window|T1564.003: Hidden Window]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[IMAPLoader](https://attack.mitre.org/software/S1152) hides the Windows Console window created by its execution by directly importing the `kernel32.dll` and `user32.dll` libraries `GetConsoleWindow` and `ShowWindow` APIs.(Citation: PWC Yellow Liderc 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b5c99a08-a5ab-41fc-88fa-1f3d3f9da504`.
