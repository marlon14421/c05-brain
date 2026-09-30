---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0834"
target_object: "T1608.002"
stix_relationship_id: "relationship--c84d14c7-448c-4eae-afa5-58ff22ab31f0"
---
# Relationship 1840: DET0834 — detects → T1608.002

**Source object:** [[01 ATT&CK/DET0834 - Detection of Upload Tool|DET0834: Detection of Upload Tool]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1608.002 - Upload Tool|T1608.002: Upload Tool]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c84d14c7-448c-4eae-afa5-58ff22ab31f0`.
