---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0261"
target_object: "T1074.001"
stix_relationship_id: "relationship--2d994d7b-b354-4824-bee6-7d3161fe0e8d"
---
# Relationship 1581: DET0261 — detects → T1074.001

**Source object:** [[01 ATT&CK/DET0261 - Detection of Local Data Staging Prior to Exfiltration|DET0261: Detection of Local Data Staging Prior to Exfiltration]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1074.001 - Local Data Staging|T1074.001: Local Data Staging]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2d994d7b-b354-4824-bee6-7d3161fe0e8d`.
