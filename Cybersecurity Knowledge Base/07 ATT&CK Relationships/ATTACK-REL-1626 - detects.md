---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0578"
target_object: "T1619"
stix_relationship_id: "relationship--283829b4-a0ef-4dd8-b9d3-d35d2017b96e"
---
# Relationship 1626: DET0578 — detects → T1619

**Source object:** [[01 ATT&CK/DET0578 - Detection Strategy for Cloud Storage Object Discovery|DET0578: Detection Strategy for Cloud Storage Object Discovery]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1619 - Cloud Storage Object Discovery|T1619: Cloud Storage Object Discovery]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--283829b4-a0ef-4dd8-b9d3-d35d2017b96e`.
