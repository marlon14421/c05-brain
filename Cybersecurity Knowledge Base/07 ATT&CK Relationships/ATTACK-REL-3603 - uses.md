---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0699"
target_object: "T1573.002"
stix_relationship_id: "relationship--3843a4eb-cf3b-4cf9-91db-5a481ce3f32d"
---
# Relationship 3603: S0699 — uses → T1573.002

**Source object:** [[01 ATT&CK/S0699 - Mythic|S0699: Mythic]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.002 - Asymmetric Cryptography|T1573.002: Asymmetric Cryptography]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Mythic](https://attack.mitre.org/software/S0699) supports SSL encrypted C2.(Citation: Mythc Documentation)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3843a4eb-cf3b-4cf9-91db-5a481ce3f32d`.
