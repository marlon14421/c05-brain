---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0094"
target_object: "S1201"
stix_relationship_id: "relationship--fd72611b-1995-45a2-9b89-26f56823eb6b"
---
# Relationship 4950: G0094 — uses → S1201

**Source object:** [[01 ATT&CK/G0094 - Kimsuky|G0094: Kimsuky]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1201 - TRANSLATEXT|S1201: TRANSLATEXT]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: Zscaler Kimsuky TRANSLATEXT)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fd72611b-1995-45a2-9b89-26f56823eb6b`.
