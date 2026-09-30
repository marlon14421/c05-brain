---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0133"
target_object: "T1219.001"
stix_relationship_id: "relationship--1c74bb94-725b-430e-a4f4-166fc9bcee7f"
---
# Relationship 1457: DET0133 — detects → T1219.001

**Source object:** [[01 ATT&CK/DET0133 - IDE Tunneling Detection via Process, File, and Network Behaviors|DET0133: IDE Tunneling Detection via Process, File, and Network Behaviors]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1219.001 - IDE Tunneling|T1219.001: IDE Tunneling]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1c74bb94-725b-430e-a4f4-166fc9bcee7f`.
