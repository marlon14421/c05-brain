---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0059"
target_object: "S0096"
stix_relationship_id: "relationship--703694f1-755e-4e3f-aff2-f623ec842693"
---
# Relationship 3974: G0059 — uses → S0096

**Source object:** [[01 ATT&CK/G0059 - Magic Hound|G0059: Magic Hound]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0096 - Systeminfo|S0096: Systeminfo]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: DFIR Phosphorus November 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--703694f1-755e-4e3f-aff2-f623ec842693`.
