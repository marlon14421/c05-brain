---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0411"
target_object: "T1665"
stix_relationship_id: "relationship--eccb3880-3ab0-4332-b19a-c9b5c180e39c"
---
# Relationship 1716: DET0411 — detects → T1665

**Source object:** [[01 ATT&CK/DET0411 - Detection Strategy for Hide Infrastructure|DET0411: Detection Strategy for Hide Infrastructure]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1665 - Hide Infrastructure|T1665: Hide Infrastructure]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--eccb3880-3ab0-4332-b19a-c9b5c180e39c`.
