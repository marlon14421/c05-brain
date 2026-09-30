---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0032"
target_object: "S0593"
stix_relationship_id: "relationship--b78b74a4-7fe3-4de5-9aba-b176f1929a7c"
---
# Relationship 3594: G0032 — uses → S0593

**Source object:** [[01 ATT&CK/G0032 - Lazarus Group|G0032: Lazarus Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0593 - ECCENTRICBANDWAGON|S0593: ECCENTRICBANDWAGON]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: CISA EB Aug 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b78b74a4-7fe3-4de5-9aba-b176f1929a7c`.
