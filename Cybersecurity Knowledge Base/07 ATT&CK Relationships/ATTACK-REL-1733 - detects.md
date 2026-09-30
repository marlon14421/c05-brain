---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0130"
target_object: "T1555.006"
stix_relationship_id: "relationship--e3e6b388-bf62-460b-af91-2cedf78cf9f4"
---
# Relationship 1733: DET0130 — detects → T1555.006

**Source object:** [[01 ATT&CK/DET0130 - Detect Unauthorized Access to Cloud Secrets Management Stores|DET0130: Detect Unauthorized Access to Cloud Secrets Management Stores]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1555.006 - Cloud Secrets Management Stores|T1555.006: Cloud Secrets Management Stores]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e3e6b388-bf62-460b-af91-2cedf78cf9f4`.
