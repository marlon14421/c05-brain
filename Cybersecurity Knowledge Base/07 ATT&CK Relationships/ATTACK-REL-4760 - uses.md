---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1179"
target_object: "T1070.004"
stix_relationship_id: "relationship--c9c643a3-f3f7-4a40-8ddc-5cfd27363197"
---
# Relationship 4760: S1179 — uses → T1070.004

**Source object:** [[01 ATT&CK/S1179 - Exbyte|S1179: Exbyte]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Exbyte](https://attack.mitre.org/software/S1179) will self-delete if a hard-coded configuration file is not found.(Citation: Microsoft BlackByte 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c9c643a3-f3f7-4a40-8ddc-5cfd27363197`.
