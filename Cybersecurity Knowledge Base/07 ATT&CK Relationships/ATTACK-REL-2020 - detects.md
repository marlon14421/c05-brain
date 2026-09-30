---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0244"
target_object: "T1037.002"
stix_relationship_id: "relationship--397f9c3a-bc7c-44b0-9931-9d2f877073c7"
---
# Relationship 2020: DET0244 — detects → T1037.002

**Source object:** [[01 ATT&CK/DET0244 - Detection Strategy for Login Hook Persistence on macOS|DET0244: Detection Strategy for Login Hook Persistence on macOS]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1037.002 - Login Hook|T1037.002: Login Hook]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--397f9c3a-bc7c-44b0-9931-9d2f877073c7`.
