---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0001"
target_object: "S0012"
stix_relationship_id: "relationship--abe1a402-9ad5-43d0-9e5d-cabe4269fc06"
---
# Relationship 3351: G0001 — uses → S0012

**Source object:** [[01 ATT&CK/G0001 - Axiom|G0001: Axiom]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0012 - PoisonIvy|S0012: PoisonIvy]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: Cisco Group 72)(Citation: Novetta-Axiom)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--abe1a402-9ad5-43d0-9e5d-cabe4269fc06`.
