---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0221"
target_object: "T1123"
stix_relationship_id: "relationship--a98091ed-435e-4359-913c-c1a86e4113af"
---
# Relationship 1987: DET0221 — detects → T1123

**Source object:** [[01 ATT&CK/DET0221 - Behavioral Detection Strategy for T1123 Audio Capture Across Windows, Linux, macOS|DET0221: Behavioral Detection Strategy for T1123 Audio Capture Across Windows, Linux, macOS]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1123 - Audio Capture|T1123: Audio Capture]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a98091ed-435e-4359-913c-c1a86e4113af`.
