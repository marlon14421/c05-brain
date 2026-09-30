---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "attributed-to"
source_object: "C0024"
target_object: "G0016"
stix_relationship_id: "relationship--3b2680f0-aa69-4766-ab41-9123373ffa4e"
---
# Relationship 2642: C0024 — attributed-to → G0016

**Source object:** [[01 ATT&CK/C0024 - SolarWinds Compromise|C0024: SolarWinds Compromise]]  
**Relationship:** `attributed-to`  
**Target object:** [[01 ATT&CK/G0016 - APT29|G0016: APT29]]

## Meaning for defensive analysis

Records an attribution relationship in the source catalog; attribution is probabilistic and should not be treated as certainty.

## Source description

(Citation: NSA Joint Advisory SVR SolarWinds April 2021)(Citation: UK NSCS Russia SolarWinds April 2021)(Citation: Mandiant UNC2452 APT29 April 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3b2680f0-aa69-4766-ab41-9123373ffa4e`.
