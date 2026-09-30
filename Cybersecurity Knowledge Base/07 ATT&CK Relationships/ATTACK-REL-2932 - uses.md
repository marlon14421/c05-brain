---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0139"
target_object: "T1552.001"
stix_relationship_id: "relationship--e830611d-a7c5-446c-a5a7-ec1062bb3f53"
---
# Relationship 2932: G0139 — uses → T1552.001

**Source object:** [[01 ATT&CK/G0139 - TeamTNT|G0139: TeamTNT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1552.001 - Credentials In Files|T1552.001: Credentials In Files]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TeamTNT](https://attack.mitre.org/groups/G0139) has searched for unsecured AWS credentials and Docker API credentials.(Citation: Cado Security TeamTNT Worm August 2020)(Citation: Trend Micro TeamTNT)(Citation: Cisco Talos Intelligence Group)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e830611d-a7c5-446c-a5a7-ec1062bb3f53`.
