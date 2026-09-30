---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0850"
target_object: "T1588"
stix_relationship_id: "relationship--ff6ff6a3-7bdf-449c-ac49-04e76dc389c5"
---
# Relationship 1502: DET0850 — detects → T1588

**Source object:** [[01 ATT&CK/DET0850 - Detection of Obtain Capabilities|DET0850: Detection of Obtain Capabilities]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1588 - Obtain Capabilities|T1588: Obtain Capabilities]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ff6ff6a3-7bdf-449c-ac49-04e76dc389c5`.
