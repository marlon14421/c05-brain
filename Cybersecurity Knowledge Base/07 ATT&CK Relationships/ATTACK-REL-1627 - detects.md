---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0471"
target_object: "T1080"
stix_relationship_id: "relationship--f4069924-bd74-4ec0-a2ef-af02e966dcea"
---
# Relationship 1627: DET0471 — detects → T1080

**Source object:** [[01 ATT&CK/DET0471 - Detection of Tainted Content Written to Shared Storage|DET0471: Detection of Tainted Content Written to Shared Storage]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1080 - Taint Shared Content|T1080: Taint Shared Content]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f4069924-bd74-4ec0-a2ef-af02e966dcea`.
