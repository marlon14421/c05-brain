---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0158"
target_object: "T1218.007"
stix_relationship_id: "relationship--1d94bde6-737e-4e6f-8521-fcb315057931"
---
# Relationship 1937: DET0158 — detects → T1218.007

**Source object:** [[01 ATT&CK/DET0158 - Detection of Msiexec Abuse for Local, Network, and DLL Execution|DET0158: Detection of Msiexec Abuse for Local, Network, and DLL Execution]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1218.007 - Msiexec|T1218.007: Msiexec]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1d94bde6-737e-4e6f-8521-fcb315057931`.
