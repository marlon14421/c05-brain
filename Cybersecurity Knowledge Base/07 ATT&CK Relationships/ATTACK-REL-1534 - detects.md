---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0173"
target_object: "T1499.002"
stix_relationship_id: "relationship--32595fc5-b57a-4052-8e1c-a2d01d6e3d14"
---
# Relationship 1534: DET0173 — detects → T1499.002

**Source object:** [[01 ATT&CK/DET0173 - Detection Strategy for Endpoint DoS via Service Exhaustion Flood|DET0173: Detection Strategy for Endpoint DoS via Service Exhaustion Flood]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1499.002 - Service Exhaustion Flood|T1499.002: Service Exhaustion Flood]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--32595fc5-b57a-4052-8e1c-a2d01d6e3d14`.
