---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1247"
target_object: "T1480.002"
stix_relationship_id: "relationship--0cc89d3e-9fe9-42f1-acb5-a7bce55840c0"
---
# Relationship 4125: S1247 — uses → T1480.002

**Source object:** [[01 ATT&CK/S1247 - Embargo|S1247: Embargo]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1480.002 - Mutual Exclusion|T1480.002: Mutual Exclusion]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Embargo](https://attack.mitre.org/software/S1247) has utilized a hardcoded mutex name of “LoadUpOnGunsBringYourFriends” using the `CreateMutexW()` function.(Citation: Cyble Embargo Ransomware May 2024) [Embargo](https://attack.mitre.org/software/S1247) has also utilized a hardcoded mutex name of “IntoTheFloodAgainSameOldTrip."(Citation: ESET Embargo Ransomware October 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0cc89d3e-9fe9-42f1-acb5-a7bce55840c0`.
