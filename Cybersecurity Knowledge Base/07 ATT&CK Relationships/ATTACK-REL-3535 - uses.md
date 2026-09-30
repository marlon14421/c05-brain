---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0610"
target_object: "T1132.001"
stix_relationship_id: "relationship--0b71ce5b-7174-4491-8890-c699d93907e7"
---
# Relationship 3535: S0610 — uses → T1132.001

**Source object:** [[01 ATT&CK/S0610 - SideTwist|S0610: SideTwist]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1132.001 - Standard Encoding|T1132.001: Standard Encoding]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SideTwist](https://attack.mitre.org/software/S0610) has used Base64 for encoded C2 traffic.(Citation: Check Point APT34 April 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0b71ce5b-7174-4491-8890-c699d93907e7`.
