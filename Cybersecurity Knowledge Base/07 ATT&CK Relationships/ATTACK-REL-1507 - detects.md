---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0838"
target_object: "T1583.003"
stix_relationship_id: "relationship--ed1bc980-2a74-4682-a3c1-cef8549f0c54"
---
# Relationship 1507: DET0838 — detects → T1583.003

**Source object:** [[01 ATT&CK/DET0838 - Detection of Virtual Private Server|DET0838: Detection of Virtual Private Server]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1583.003 - Virtual Private Server|T1583.003: Virtual Private Server]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ed1bc980-2a74-4682-a3c1-cef8549f0c54`.
