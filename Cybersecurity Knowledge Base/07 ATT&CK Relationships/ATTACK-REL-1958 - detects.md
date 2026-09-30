---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0015"
target_object: "T1668"
stix_relationship_id: "relationship--301352ff-7025-44a2-b4ef-303d75d8f18a"
---
# Relationship 1958: DET0015 — detects → T1668

**Source object:** [[01 ATT&CK/DET0015 - Detection Strategy for Exclusive Control|DET0015: Detection Strategy for Exclusive Control]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1668 - Exclusive Control|T1668: Exclusive Control]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--301352ff-7025-44a2-b4ef-303d75d8f18a`.
