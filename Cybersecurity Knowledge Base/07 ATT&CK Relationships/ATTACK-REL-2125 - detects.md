---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0230"
target_object: "T1553.002"
stix_relationship_id: "relationship--e938af0c-04ae-43d6-bd23-5ee204c8e306"
---
# Relationship 2125: DET0230 — detects → T1553.002

**Source object:** [[01 ATT&CK/DET0230 - Detect Suspicious or Malicious Code Signing Abuse|DET0230: Detect Suspicious or Malicious Code Signing Abuse]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1553.002 - Code Signing|T1553.002: Code Signing]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e938af0c-04ae-43d6-bd23-5ee204c8e306`.
