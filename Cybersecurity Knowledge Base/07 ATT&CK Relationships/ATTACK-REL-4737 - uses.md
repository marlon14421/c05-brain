---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1130"
target_object: "T1204"
stix_relationship_id: "relationship--a6a6e8e2-c9c2-40b9-b410-ea84b2c43caf"
---
# Relationship 4737: S1130 — uses → T1204

**Source object:** [[01 ATT&CK/S1130 - Raspberry Robin|S1130: Raspberry Robin]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204 - User Execution|T1204: User Execution]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Raspberry Robin](https://attack.mitre.org/software/S1130) execution can rely on users directly interacting with malicious LNK files.(Citation: Microsoft RaspberryRobin 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a6a6e8e2-c9c2-40b9-b410-ea84b2c43caf`.
