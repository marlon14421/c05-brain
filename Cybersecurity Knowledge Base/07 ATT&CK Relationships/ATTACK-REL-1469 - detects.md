---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0225"
target_object: "T1547.008"
stix_relationship_id: "relationship--3c2ece76-c163-48ab-8c7e-8780ffd72461"
---
# Relationship 1469: DET0225 — detects → T1547.008

**Source object:** [[01 ATT&CK/DET0225 - Detect unauthorized LSASS driver persistence via LSA plugin abuse (Windows)|DET0225: Detect unauthorized LSASS driver persistence via LSA plugin abuse (Windows)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1547.008 - LSASS Driver|T1547.008: LSASS Driver]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3c2ece76-c163-48ab-8c7e-8780ffd72461`.
