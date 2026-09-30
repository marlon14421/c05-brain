---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0032"
target_object: "T1564.001"
stix_relationship_id: "relationship--1c135a0c-a6dc-404e-8a38-d4db97d5eb4b"
---
# Relationship 1741: DET0032 — detects → T1564.001

**Source object:** [[01 ATT&CK/DET0032 - Detection Strategy for Hidden Files and Directories|DET0032: Detection Strategy for Hidden Files and Directories]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1564.001 - Hidden Files and Directories|T1564.001: Hidden Files and Directories]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1c135a0c-a6dc-404e-8a38-d4db97d5eb4b`.
