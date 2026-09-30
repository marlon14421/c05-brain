---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0494"
target_object: "T1600.002"
stix_relationship_id: "relationship--82c53252-e692-40eb-a345-f91ee83fb49a"
---
# Relationship 1936: DET0494 — detects → T1600.002

**Source object:** [[01 ATT&CK/DET0494 - Detection Strategy for Weaken Encryption- Disable Crypto Hardware on Network Devices|DET0494: Detection Strategy for Weaken Encryption: Disable Crypto Hardware on Network Devices]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1600.002 - Disable Crypto Hardware|T1600.002: Disable Crypto Hardware]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--82c53252-e692-40eb-a345-f91ee83fb49a`.
