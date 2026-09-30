---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0046"
target_object: "T1102.002"
stix_relationship_id: "relationship--233d1a32-f826-4705-a535-806edee8a5aa"
---
# Relationship 2896: S0046 — uses → T1102.002

**Source object:** [[01 ATT&CK/S0046 - CozyCar|S0046: CozyCar]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102.002 - Bidirectional Communication|T1102.002: Bidirectional Communication]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[CozyCar](https://attack.mitre.org/software/S0046) uses Twitter as a backup C2 channel to Twitter accounts specified in its configuration file.(Citation: F-Secure CozyDuke)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--233d1a32-f826-4705-a535-806edee8a5aa`.
