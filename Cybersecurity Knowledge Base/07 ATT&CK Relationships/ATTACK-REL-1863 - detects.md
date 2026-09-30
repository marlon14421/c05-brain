---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0430"
target_object: "T1555"
stix_relationship_id: "relationship--d682a414-3dc3-4bf0-b6de-cdb3d91d375c"
---
# Relationship 1863: DET0430 — detects → T1555

**Source object:** [[01 ATT&CK/DET0430 - Detect Credentials Access from Password Stores|DET0430: Detect Credentials Access from Password Stores]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1555 - Credentials from Password Stores|T1555: Credentials from Password Stores]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d682a414-3dc3-4bf0-b6de-cdb3d91d375c`.
