---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0140"
target_object: "S0262"
stix_relationship_id: "relationship--878ff6f7-d372-4559-a114-8858eb2682d4"
---
# Relationship 4200: G0140 — uses → S0262

**Source object:** [[01 ATT&CK/G0140 - LazyScripter|G0140: LazyScripter]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0262 - QuasarRAT|S0262: QuasarRAT]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: MalwareBytes LazyScripter Feb 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--878ff6f7-d372-4559-a114-8858eb2682d4`.
