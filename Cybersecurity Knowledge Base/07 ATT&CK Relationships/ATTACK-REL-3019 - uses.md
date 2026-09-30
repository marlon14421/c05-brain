---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0029"
target_object: "S1119"
stix_relationship_id: "relationship--fa755fbd-3f98-4795-ba15-d1f80983b4d6"
---
# Relationship 3019: C0029 — uses → S1119

**Source object:** [[01 ATT&CK/C0029 - Cutting Edge|C0029: Cutting Edge]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1119 - LIGHTWIRE|S1119: LIGHTWIRE]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: Mandiant Cutting Edge Part 2 January 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fa755fbd-3f98-4795-ba15-d1f80983b4d6`.
