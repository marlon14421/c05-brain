---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0040"
target_object: "T1070.009"
stix_relationship_id: "relationship--b1a5df9f-7a6e-48f4-b779-cc11e9db0e24"
---
# Relationship 1614: DET0040 — detects → T1070.009

**Source object:** [[01 ATT&CK/DET0040 - Detection of Persistence Artifact Removal Across Host Platforms|DET0040: Detection of Persistence Artifact Removal Across Host Platforms]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1070.009 - Clear Persistence|T1070.009: Clear Persistence]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b1a5df9f-7a6e-48f4-b779-cc11e9db0e24`.
