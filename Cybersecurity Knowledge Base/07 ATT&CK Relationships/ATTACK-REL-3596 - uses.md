---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0330"
target_object: "T1070.004"
stix_relationship_id: "relationship--ba8900d2-1a18-4f44-916d-08b93dc74d9c"
---
# Relationship 3596: S0330 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0330 - Zeus Panda|S0330: Zeus Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Zeus Panda](https://attack.mitre.org/software/S0330) has a command to delete a file. It also can uninstall scripts and delete files to cover its track.(Citation: GDATA Zeus Panda June 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ba8900d2-1a18-4f44-916d-08b93dc74d9c`.
