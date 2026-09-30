---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0146"
target_object: "T1485"
stix_relationship_id: "relationship--31ece083-4856-4057-bfca-5dd17221b34b"
---
# Relationship 1775: DET0146 — detects → T1485

**Source object:** [[01 ATT&CK/DET0146 - Detection of Data Destruction Across Platforms via Mass Overwrite and Deletion Patter|DET0146: Detection of Data Destruction Across Platforms via Mass Overwrite and Deletion Patterns]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1485 - Data Destruction|T1485: Data Destruction]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--31ece083-4856-4057-bfca-5dd17221b34b`.
