---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0213"
target_object: "T1030"
stix_relationship_id: "relationship--cc688a88-f152-49d3-a148-806fd9348d44"
---
# Relationship 1909: DET0213 — detects → T1030

**Source object:** [[01 ATT&CK/DET0213 - Detection Strategy for Data Transfer Size Limits and Chunked Exfiltration|DET0213: Detection Strategy for Data Transfer Size Limits and Chunked Exfiltration]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1030 - Data Transfer Size Limits|T1030: Data Transfer Size Limits]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cc688a88-f152-49d3-a148-806fd9348d44`.
