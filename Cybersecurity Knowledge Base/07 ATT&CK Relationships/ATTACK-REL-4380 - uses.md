---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0016"
target_object: "S0565"
stix_relationship_id: "relationship--a45bd763-a162-4b02-86f2-6042ff0eaa4a"
---
# Relationship 4380: G0016 — uses → S0565

**Source object:** [[01 ATT&CK/G0016 - APT29|G0016: APT29]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0565 - Raindrop|S0565: Raindrop]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: Symantec RAINDROP January 2021)(Citation: MSTIC Nobelium Toolset May 2021)(Citation: Secureworks IRON RITUAL Profile)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a45bd763-a162-4b02-86f2-6042ff0eaa4a`.
