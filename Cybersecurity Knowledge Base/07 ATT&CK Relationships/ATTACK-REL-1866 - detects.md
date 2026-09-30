---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0431"
target_object: "T1684.002"
stix_relationship_id: "relationship--3fab8a8b-0bd5-489a-8fe2-5dfef5b805e2"
---
# Relationship 1866: DET0431 — detects → T1684.002

**Source object:** [[01 ATT&CK/DET0431 - Detection Strategy for Email Spoofing|DET0431: Detection Strategy for Email Spoofing]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1684.002 - Email Spoofing|T1684.002: Email Spoofing]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3fab8a8b-0bd5-489a-8fe2-5dfef5b805e2`.
