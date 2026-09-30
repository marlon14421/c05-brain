---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9038"
target_object: "T1083"
stix_relationship_id: "relationship--5f013e67-6f7b-4ea5-86d4-91940f3b74cb"
---
# Relationship 3950: S9038 — uses → T1083

**Source object:** [[01 ATT&CK/S9038 - DynoWiper|S9038: DynoWiper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[DynoWiper](https://attack.mitre.org/software/S9038) has used the Microsoft Windows native `FindFirstFile()` and `FindNextFile()` to recursively enumerate directories and files on the system.(Citation: CERT Polska)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5f013e67-6f7b-4ea5-86d4-91940f3b74cb`.
