---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0378"
target_object: "T1027"
stix_relationship_id: "relationship--f1b0ce50-319c-455f-a8b2-a90f32310364"
---
# Relationship 1907: DET0378 — detects → T1027

**Source object:** [[01 ATT&CK/DET0378 - Behavioral Detection of Obfuscated Files or Information|DET0378: Behavioral Detection of Obfuscated Files or Information]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f1b0ce50-319c-455f-a8b2-a90f32310364`.
