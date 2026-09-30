---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0286"
target_object: "T1684.001"
stix_relationship_id: "relationship--1760c251-517e-46a9-b97a-325a97d1a3d1"
---
# Relationship 1983: DET0286 — detects → T1684.001

**Source object:** [[01 ATT&CK/DET0286 - Detection Strategy for Impersonation|DET0286: Detection Strategy for Impersonation]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1684.001 - Impersonation|T1684.001: Impersonation]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1760c251-517e-46a9-b97a-325a97d1a3d1`.
