---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0042"
target_object: "T1102.002"
stix_relationship_id: "relationship--8c9f23e6-2665-45b3-9c28-53a9335b16ce"
---
# Relationship 2840: S0042 — uses → T1102.002

**Source object:** [[01 ATT&CK/S0042 - LOWBALL|S0042: LOWBALL]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102.002 - Bidirectional Communication|T1102.002: Bidirectional Communication]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[LOWBALL](https://attack.mitre.org/software/S0042) uses the Dropbox cloud storage service for command and control.(Citation: FireEye admin@338)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8c9f23e6-2665-45b3-9c28-53a9335b16ce`.
