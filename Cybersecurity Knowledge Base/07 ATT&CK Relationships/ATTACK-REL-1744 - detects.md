---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0551"
target_object: "T1110.001"
stix_relationship_id: "relationship--371ec2aa-7498-4e77-8bfe-bb97f04a15f9"
---
# Relationship 1744: DET0551 — detects → T1110.001

**Source object:** [[01 ATT&CK/DET0551 - Password Guessing via Multi-Source Authentication Failure Correlation|DET0551: Password Guessing via Multi-Source Authentication Failure Correlation]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1110.001 - Password Guessing|T1110.001: Password Guessing]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--371ec2aa-7498-4e77-8bfe-bb97f04a15f9`.
