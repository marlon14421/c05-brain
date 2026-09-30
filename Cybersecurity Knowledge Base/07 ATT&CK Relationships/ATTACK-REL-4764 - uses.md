---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0051"
target_object: "T1074.001"
stix_relationship_id: "relationship--757936cb-468c-4b60-a996-8089c77cea62"
---
# Relationship 4764: C0051 — uses → T1074.001

**Source object:** [[01 ATT&CK/C0051 - APT28 Nearest Neighbor Campaign|C0051: APT28 Nearest Neighbor Campaign]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1074.001 - Local Data Staging|T1074.001: Local Data Staging]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [APT28 Nearest Neighbor Campaign](https://attack.mitre.org/campaigns/C0051), [APT28](https://attack.mitre.org/groups/G0007) staged captured credential information in the C:\ProgramData directory.(Citation: Nearest Neighbor Volexity)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--757936cb-468c-4b60-a996-8089c77cea62`.
