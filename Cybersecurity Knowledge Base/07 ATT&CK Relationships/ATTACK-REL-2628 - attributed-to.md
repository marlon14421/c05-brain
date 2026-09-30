---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "attributed-to"
source_object: "C0052"
target_object: "G1023"
stix_relationship_id: "relationship--7e632f9c-c55b-4aef-8bdc-56e0317375ee"
---
# Relationship 2628: C0052 — attributed-to → G1023

**Source object:** [[01 ATT&CK/C0052 - SPACEHOP Activity|C0052: SPACEHOP Activity]]  
**Relationship:** `attributed-to`  
**Target object:** [[01 ATT&CK/G1023 - APT5|G1023: APT5]]

## Meaning for defensive analysis

Records an attribution relationship in the source catalog; attribution is probabilistic and should not be treated as certainty.

## Source description

(Citation: ORB Mandiant)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7e632f9c-c55b-4aef-8bdc-56e0317375ee`.
