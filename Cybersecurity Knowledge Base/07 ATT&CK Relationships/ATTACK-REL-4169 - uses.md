---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0027"
target_object: "T1087.001"
stix_relationship_id: "relationship--b2dbbb46-9659-4277-8753-c469c4bfe409"
---
# Relationship 4169: G0027 — uses → T1087.001

**Source object:** [[01 ATT&CK/G0027 - Threat Group-3390|G0027: Threat Group-3390]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1087.001 - Local Account|T1087.001: Local Account]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Threat Group-3390](https://attack.mitre.org/groups/G0027) has used net user to conduct internal discovery of systems.(Citation: SecureWorks BRONZE UNION June 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b2dbbb46-9659-4277-8753-c469c4bfe409`.
