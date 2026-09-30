---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1011"
target_object: "T1597"
stix_relationship_id: "relationship--a42c4b1f-e145-4bf2-bd5e-fe65ff3e1a24"
---
# Relationship 3679: G1011 — uses → T1597

**Source object:** [[01 ATT&CK/G1011 - EXOTIC LILY|G1011: EXOTIC LILY]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1597 - Search Closed Sources|T1597: Search Closed Sources]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[EXOTIC LILY](https://attack.mitre.org/groups/G1011) has searched for information on targeted individuals on business databases including RocketReach and CrunchBase.(Citation: Google EXOTIC LILY March 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a42c4b1f-e145-4bf2-bd5e-fe65ff3e1a24`.
