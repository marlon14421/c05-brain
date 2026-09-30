---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1054"
target_object: "S9022"
stix_relationship_id: "relationship--0ef43f4a-6781-4e70-a09c-368283ab411c"
---
# Relationship 4330: G1054 — uses → S9022

**Source object:** [[01 ATT&CK/G1054 - MirrorFace|G1054: MirrorFace]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S9022 - MirrorStealer|S9022: MirrorStealer]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[MirrorFace](https://attack.mitre.org/groups/G1054) has used [MirrorStealer](https://attack.mitre.org/software/S9022) to harvest credentials.(Citation: ESET MirrorFace DEC 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0ef43f4a-6781-4e70-a09c-368283ab411c`.
