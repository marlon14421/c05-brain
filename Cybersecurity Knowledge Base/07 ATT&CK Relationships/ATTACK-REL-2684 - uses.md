---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0140"
target_object: "S0250"
stix_relationship_id: "relationship--c7972596-a87d-48fd-bd6f-f140e16f99a6"
---
# Relationship 2684: G0140 — uses → S0250

**Source object:** [[01 ATT&CK/G0140 - LazyScripter|G0140: LazyScripter]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0250 - Koadic|S0250: Koadic]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: MalwareBytes LazyScripter Feb 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c7972596-a87d-48fd-bd6f-f140e16f99a6`.
