---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0091"
target_object: "T1125"
stix_relationship_id: "relationship--5e60c70a-7b2f-45b8-b7d4-80e214acfb2d"
---
# Relationship 3506: G0091 — uses → T1125

**Source object:** [[01 ATT&CK/G0091 - Silence|G0091: Silence]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1125 - Video Capture|T1125: Video Capture]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Silence](https://attack.mitre.org/groups/G0091) has been observed making videos of victims to observe bank employees day to day activities.(Citation: SecureList Silence Nov 2017)(Citation: Group IB Silence Sept 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5e60c70a-7b2f-45b8-b7d4-80e214acfb2d`.
