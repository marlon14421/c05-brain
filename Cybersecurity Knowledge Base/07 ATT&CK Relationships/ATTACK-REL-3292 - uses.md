---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0051"
target_object: "S0363"
stix_relationship_id: "relationship--1e809121-085d-419e-a763-c9e2309af074"
---
# Relationship 3292: G0051 — uses → S0363

**Source object:** [[01 ATT&CK/G0051 - FIN10|G0051: FIN10]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0363 - Empire|S0363: Empire]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: FireEye FIN10 June 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1e809121-085d-419e-a763-c9e2309af074`.
