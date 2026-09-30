---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1033"
target_object: "T1583.001"
stix_relationship_id: "relationship--2e13c903-72e3-4ed7-a4b5-8441793a36e6"
---
# Relationship 2988: G1033 — uses → T1583.001

**Source object:** [[01 ATT&CK/G1033 - Star Blizzard|G1033: Star Blizzard]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1583.001 - Domains|T1583.001: Domains]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Star Blizzard](https://attack.mitre.org/groups/G1033) has registered domains using randomized words and with names resembling legitimate organizations.(Citation: CISA Star Blizzard Advisory December 2023)(Citation: StarBlizzard)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2e13c903-72e3-4ed7-a4b5-8441793a36e6`.
