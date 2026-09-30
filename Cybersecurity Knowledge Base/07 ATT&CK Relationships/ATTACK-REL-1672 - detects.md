---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0426"
target_object: "T1006"
stix_relationship_id: "relationship--6748068f-c437-42b7-b09d-d057a1f49dc1"
---
# Relationship 1672: DET0426 — detects → T1006

**Source object:** [[01 ATT&CK/DET0426 - Detection of Direct Volume Access for File System Evasion|DET0426: Detection of Direct Volume Access for File System Evasion]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1006 - Direct Volume Access|T1006: Direct Volume Access]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6748068f-c437-42b7-b09d-d057a1f49dc1`.
