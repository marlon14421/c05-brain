---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0883"
target_object: "T1584.005"
stix_relationship_id: "relationship--3377c5db-343a-4a3b-86a1-2b4a94399d27"
---
# Relationship 1485: DET0883 — detects → T1584.005

**Source object:** [[01 ATT&CK/DET0883 - Detection of Botnet|DET0883: Detection of Botnet]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1584.005 - Botnet|T1584.005: Botnet]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3377c5db-343a-4a3b-86a1-2b4a94399d27`.
