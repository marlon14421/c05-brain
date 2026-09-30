---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1134"
target_object: "T1036.004"
stix_relationship_id: "relationship--60692cc5-ca97-4c1d-8011-8dbe111ca8f4"
---
# Relationship 2713: S1134 — uses → T1036.004

**Source object:** [[01 ATT&CK/S1134 - DEADWOOD|S1134: DEADWOOD]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.004 - Masquerade Task or Service|T1036.004: Masquerade Task or Service]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[DEADWOOD](https://attack.mitre.org/software/S1134) will attempt to masquerade its service execution using benign-looking names such as ScDeviceEnums .(Citation: SentinelOne Agrius 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--60692cc5-ca97-4c1d-8011-8dbe111ca8f4`.
