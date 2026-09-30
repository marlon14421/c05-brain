---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0404"
target_object: "T1547.004"
stix_relationship_id: "relationship--1da61cf7-c299-443f-8987-b6a25b805915"
---
# Relationship 1819: DET0404 — detects → T1547.004

**Source object:** [[01 ATT&CK/DET0404 - Detect Winlogon Helper DLL Abuse via Registry and Process Artifacts on Windows|DET0404: Detect Winlogon Helper DLL Abuse via Registry and Process Artifacts on Windows]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1547.004 - Winlogon Helper DLL|T1547.004: Winlogon Helper DLL]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1da61cf7-c299-443f-8987-b6a25b805915`.
