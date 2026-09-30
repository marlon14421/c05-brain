---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0181"
target_object: "T1505.001"
stix_relationship_id: "relationship--d124d653-63e4-4f79-a45e-f96b8bfdb63f"
---
# Relationship 1558: DET0181 — detects → T1505.001

**Source object:** [[01 ATT&CK/DET0181 - Detection Strategy for SQL Stored Procedures Abuse via T1505.001|DET0181: Detection Strategy for SQL Stored Procedures Abuse via T1505.001]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1505.001 - SQL Stored Procedures|T1505.001: SQL Stored Procedures]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d124d653-63e4-4f79-a45e-f96b8bfdb63f`.
