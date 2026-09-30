---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0875"
target_object: "T1588.003"
stix_relationship_id: "relationship--f05ef52f-c0e2-434f-a298-6a0daf7be73f"
---
# Relationship 1464: DET0875 — detects → T1588.003

**Source object:** [[01 ATT&CK/DET0875 - Detection of Code Signing Certificates|DET0875: Detection of Code Signing Certificates]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1588.003 - Code Signing Certificates|T1588.003: Code Signing Certificates]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f05ef52f-c0e2-434f-a298-6a0daf7be73f`.
