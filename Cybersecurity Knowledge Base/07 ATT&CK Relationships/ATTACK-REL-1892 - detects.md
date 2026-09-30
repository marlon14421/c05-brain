---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0919"
target_object: "T1682"
stix_relationship_id: "relationship--fbdedc97-4cd0-4c7f-a82c-b4f3d0d42f31"
---
# Relationship 1892: DET0919 — detects → T1682

**Source object:** [[01 ATT&CK/DET0919 - Detection of Query Public AI Services|DET0919: Detection of Query Public AI Services]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1682 - Query Public AI Services|T1682: Query Public AI Services]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fbdedc97-4cd0-4c7f-a82c-b4f3d0d42f31`.
