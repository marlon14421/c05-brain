---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0125"
target_object: "S0020"
stix_relationship_id: "relationship--951774ce-173c-4aaf-a6e3-515ba497d523"
---
# Relationship 4318: G0125 — uses → S0020

**Source object:** [[01 ATT&CK/G0125 - HAFNIUM|G0125: HAFNIUM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0020 - China Chopper|S0020: China Chopper]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: Volexity Exchange Marauder March 2021)(Citation: FireEye Exchange Zero Days March 2021)(Citation: Rapid7 HAFNIUM Mar 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--951774ce-173c-4aaf-a6e3-515ba497d523`.
