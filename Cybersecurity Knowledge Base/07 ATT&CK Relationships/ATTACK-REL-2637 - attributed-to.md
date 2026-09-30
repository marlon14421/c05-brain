---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "attributed-to"
source_object: "C0039"
target_object: "G1017"
stix_relationship_id: "relationship--b109514b-66b3-4c06-8b1d-4f89e1f2cfde"
---
# Relationship 2637: C0039 — attributed-to → G1017

**Source object:** [[01 ATT&CK/C0039 - Versa Director Zero Day Exploitation|C0039: Versa Director Zero Day Exploitation]]  
**Relationship:** `attributed-to`  
**Target object:** [[01 ATT&CK/G1017 - Volt Typhoon|G1017: Volt Typhoon]]

## Meaning for defensive analysis

Records an attribution relationship in the source catalog; attribution is probabilistic and should not be treated as certainty.

## Source description

[Versa Director Zero Day Exploitation](https://attack.mitre.org/campaigns/C0039) was conducted by [Volt Typhoon](https://attack.mitre.org/groups/G1017) between June and August 2024.(Citation: Lumen Versa 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b109514b-66b3-4c06-8b1d-4f89e1f2cfde`.
