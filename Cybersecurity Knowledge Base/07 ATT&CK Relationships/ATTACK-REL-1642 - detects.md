---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0499"
target_object: "T1008"
stix_relationship_id: "relationship--87311c74-f1fe-403e-a646-39fa03ca756a"
---
# Relationship 1642: DET0499 — detects → T1008

**Source object:** [[01 ATT&CK/DET0499 - Behavioral Detection of Fallback or Alternate C2 Channels|DET0499: Behavioral Detection of Fallback or Alternate C2 Channels]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1008 - Fallback Channels|T1008: Fallback Channels]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--87311c74-f1fe-403e-a646-39fa03ca756a`.
