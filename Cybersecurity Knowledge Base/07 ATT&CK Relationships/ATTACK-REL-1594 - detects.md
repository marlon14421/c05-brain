---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0861"
target_object: "T1586.002"
stix_relationship_id: "relationship--396d8292-e204-48ff-bc48-4b994f94d7a6"
---
# Relationship 1594: DET0861 — detects → T1586.002

**Source object:** [[01 ATT&CK/DET0861 - Detection of Email Accounts|DET0861: Detection of Email Accounts]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1586.002 - Email Accounts|T1586.002: Email Accounts]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--396d8292-e204-48ff-bc48-4b994f94d7a6`.
