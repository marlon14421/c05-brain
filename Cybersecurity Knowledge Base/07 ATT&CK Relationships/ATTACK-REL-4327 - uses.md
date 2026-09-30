---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0067"
target_object: "S0247"
stix_relationship_id: "relationship--e6f81b9c-8fda-49f5-a944-265f5bad82ba"
---
# Relationship 4327: G0067 — uses → S0247

**Source object:** [[01 ATT&CK/G0067 - APT37|G0067: APT37]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0247 - NavRAT|S0247: NavRAT]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: Talos NavRAT May 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e6f81b9c-8fda-49f5-a944-265f5bad82ba`.
