---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "attributed-to"
source_object: "C0023"
target_object: "G0016"
stix_relationship_id: "relationship--a3adcf1b-a48a-4fab-bc61-5e0b0aeaaca6"
---
# Relationship 2624: C0023 — attributed-to → G0016

**Source object:** [[01 ATT&CK/C0023 - Operation Ghost|C0023: Operation Ghost]]  
**Relationship:** `attributed-to`  
**Target object:** [[01 ATT&CK/G0016 - APT29|G0016: APT29]]

## Meaning for defensive analysis

Records an attribution relationship in the source catalog; attribution is probabilistic and should not be treated as certainty.

## Source description

(Citation: ESET Dukes October 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a3adcf1b-a48a-4fab-bc61-5e0b0aeaaca6`.
