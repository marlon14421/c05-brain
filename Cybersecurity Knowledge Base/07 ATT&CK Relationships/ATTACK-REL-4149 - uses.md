---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0264"
target_object: "T1053.005"
stix_relationship_id: "relationship--ce459961-3a5a-45f9-b8a4-646e9b475e19"
---
# Relationship 4149: S0264 — uses → T1053.005

**Source object:** [[01 ATT&CK/S0264 - OopsIE|S0264: OopsIE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[OopsIE](https://attack.mitre.org/software/S0264) creates a scheduled task to run itself every three minutes.(Citation: Unit 42 OopsIE! Feb 2018)(Citation: Unit 42 OilRig Sept 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ce459961-3a5a-45f9-b8a4-646e9b475e19`.
