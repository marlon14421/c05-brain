---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0315"
target_object: "T1137.002"
stix_relationship_id: "relationship--579ccb1f-91d2-4933-9067-6f07af17446d"
---
# Relationship 1908: DET0315 — detects → T1137.002

**Source object:** [[01 ATT&CK/DET0315 - Detect Persistence via Office Test Registry DLL Injection|DET0315: Detect Persistence via Office Test Registry DLL Injection]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1137.002 - Office Test|T1137.002: Office Test]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--579ccb1f-91d2-4933-9067-6f07af17446d`.
