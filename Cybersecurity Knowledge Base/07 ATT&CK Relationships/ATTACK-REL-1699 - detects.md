---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0534"
target_object: "T1548.006"
stix_relationship_id: "relationship--114f8e08-4e45-4e20-aad7-d7b265a9f5f2"
---
# Relationship 1699: DET0534 — detects → T1548.006

**Source object:** [[01 ATT&CK/DET0534 - TCC Database Manipulation via Launchctl and Unprotected SIP|DET0534: TCC Database Manipulation via Launchctl and Unprotected SIP]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1548.006 - TCC Manipulation|T1548.006: TCC Manipulation]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--114f8e08-4e45-4e20-aad7-d7b265a9f5f2`.
