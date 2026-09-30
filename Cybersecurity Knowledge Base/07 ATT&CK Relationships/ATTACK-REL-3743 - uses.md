---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1198"
target_object: "T1070.004"
stix_relationship_id: "relationship--f299a89c-59f1-41a6-a5d5-425edfe26f25"
---
# Relationship 3743: S1198 — uses → T1070.004

**Source object:** [[01 ATT&CK/S1198 - Gomir|S1198: Gomir]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Gomir](https://attack.mitre.org/software/S1198) deletes its original executable and terminates its original process after creating a systemd service.(Citation: Symantec Troll Stealer 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f299a89c-59f1-41a6-a5d5-425edfe26f25`.
