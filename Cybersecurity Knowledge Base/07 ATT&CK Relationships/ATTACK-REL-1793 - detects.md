---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0549"
target_object: "T1552.004"
stix_relationship_id: "relationship--8895c536-acb4-4c5c-b6dd-d4b9fe2f95b9"
---
# Relationship 1793: DET0549 — detects → T1552.004

**Source object:** [[01 ATT&CK/DET0549 - Detect Suspicious Access to Private Key Files and Export Attempts Across Platforms|DET0549: Detect Suspicious Access to Private Key Files and Export Attempts Across Platforms]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1552.004 - Private Keys|T1552.004: Private Keys]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8895c536-acb4-4c5c-b6dd-d4b9fe2f95b9`.
