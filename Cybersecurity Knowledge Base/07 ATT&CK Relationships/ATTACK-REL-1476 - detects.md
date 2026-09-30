---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0125"
target_object: "T1547.007"
stix_relationship_id: "relationship--8ec064e5-c9d4-49ec-a87e-ab164a6281db"
---
# Relationship 1476: DET0125 — detects → T1547.007

**Source object:** [[01 ATT&CK/DET0125 - Detect persistence via reopened application plist modification (macOS)|DET0125: Detect persistence via reopened application plist modification (macOS)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1547.007 - Re-opened Applications|T1547.007: Re-opened Applications]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8ec064e5-c9d4-49ec-a87e-ab164a6281db`.
