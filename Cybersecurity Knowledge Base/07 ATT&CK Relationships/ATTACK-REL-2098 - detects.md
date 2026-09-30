---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0224"
target_object: "T1559.001"
stix_relationship_id: "relationship--d0ddea1d-b83d-4514-95f8-95f6d6909717"
---
# Relationship 2098: DET0224 — detects → T1559.001

**Source object:** [[01 ATT&CK/DET0224 - Detect Abuse of Component Object Model (T1559.001)|DET0224: Detect Abuse of Component Object Model (T1559.001)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1559.001 - Component Object Model|T1559.001: Component Object Model]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d0ddea1d-b83d-4514-95f8-95f6d6909717`.
