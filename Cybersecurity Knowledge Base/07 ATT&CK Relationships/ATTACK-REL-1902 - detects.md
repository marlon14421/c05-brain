---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0196"
target_object: "T1090.004"
stix_relationship_id: "relationship--1034ed90-685b-412d-baa0-6aef007d52c1"
---
# Relationship 1902: DET0196 — detects → T1090.004

**Source object:** [[01 ATT&CK/DET0196 - Domain Fronting Behavior via Mismatched TLS SNI and HTTP Host Headers|DET0196: Domain Fronting Behavior via Mismatched TLS SNI and HTTP Host Headers]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1090.004 - Domain Fronting|T1090.004: Domain Fronting]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1034ed90-685b-412d-baa0-6aef007d52c1`.
