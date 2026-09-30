---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1163"
target_object: "T1505.003"
stix_relationship_id: "relationship--b881b432-1b68-44f4-8a2c-f4eba99f2bb3"
---
# Relationship 3419: S1163 — uses → T1505.003

**Source object:** [[01 ATT&CK/S1163 - SnappyTCP|S1163: SnappyTCP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1505.003 - Web Shell|T1505.003: Web Shell]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SnappyTCP](https://attack.mitre.org/software/S1163) is a reverse TCP shell with command and control capabilities used for persistence purposes.(Citation: PWC Sea Turtle 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b881b432-1b68-44f4-8a2c-f4eba99f2bb3`.
