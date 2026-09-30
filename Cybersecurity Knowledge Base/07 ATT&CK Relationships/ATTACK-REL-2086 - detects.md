---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0858"
target_object: "T1596.005"
stix_relationship_id: "relationship--3dd6dcb2-354b-457d-bbfe-21d13eb5daeb"
---
# Relationship 2086: DET0858 — detects → T1596.005

**Source object:** [[01 ATT&CK/DET0858 - Detection of Scan Databases|DET0858: Detection of Scan Databases]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1596.005 - Scan Databases|T1596.005: Scan Databases]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3dd6dcb2-354b-457d-bbfe-21d13eb5daeb`.
