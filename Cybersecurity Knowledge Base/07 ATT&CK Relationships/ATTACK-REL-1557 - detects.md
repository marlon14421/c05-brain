---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0434"
target_object: "T1543.001"
stix_relationship_id: "relationship--0f6c39d6-ff29-4c5d-8427-53eaa02617f0"
---
# Relationship 1557: DET0434 — detects → T1543.001

**Source object:** [[01 ATT&CK/DET0434 - Detection of Launch Agent Creation or Modification on macOS|DET0434: Detection of Launch Agent Creation or Modification on macOS]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1543.001 - Launch Agent|T1543.001: Launch Agent]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0f6c39d6-ff29-4c5d-8427-53eaa02617f0`.
