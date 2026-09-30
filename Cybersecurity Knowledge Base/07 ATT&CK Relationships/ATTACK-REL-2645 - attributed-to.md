---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "attributed-to"
source_object: "C0038"
target_object: "G1055"
stix_relationship_id: "relationship--0dd04e16-ad64-4b7d-af2f-12ad644cfe3e"
---
# Relationship 2645: C0038 — attributed-to → G1055

**Source object:** [[01 ATT&CK/C0038 - HomeLand Justice|C0038: HomeLand Justice]]  
**Relationship:** `attributed-to`  
**Target object:** [[01 ATT&CK/G1055 - VOID MANTICORE|G1055: VOID MANTICORE]]

## Meaning for defensive analysis

Records an attribution relationship in the source catalog; attribution is probabilistic and should not be treated as certainty.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0dd04e16-ad64-4b7d-af2f-12ad644cfe3e`.
