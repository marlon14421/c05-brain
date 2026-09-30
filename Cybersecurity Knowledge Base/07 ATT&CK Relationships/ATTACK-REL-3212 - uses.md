---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1042"
target_object: "S0596"
stix_relationship_id: "relationship--66d8591e-c6fc-4980-be44-eb846ec58ccf"
---
# Relationship 3212: G1042 — uses → S0596

**Source object:** [[01 ATT&CK/G1042 - RedEcho|G1042: RedEcho]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0596 - ShadowPad|S0596: ShadowPad]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[RedEcho](https://attack.mitre.org/groups/G1042) has used [ShadowPad](https://attack.mitre.org/software/S0596) during intrusions.(Citation: RecordedFuture RedEcho 2021)(Citation: RecordedFuture RedEcho 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--66d8591e-c6fc-4980-be44-eb846ec58ccf`.
