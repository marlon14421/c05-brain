---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0459"
target_object: "T1612"
stix_relationship_id: "relationship--33529d4a-1eac-4346-86e0-10fd834d8811"
---
# Relationship 2139: DET0459 — detects → T1612

**Source object:** [[01 ATT&CK/DET0459 - Detection Strategy for Build Image on Host|DET0459: Detection Strategy for Build Image on Host]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1612 - Build Image on Host|T1612: Build Image on Host]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--33529d4a-1eac-4346-86e0-10fd834d8811`.
