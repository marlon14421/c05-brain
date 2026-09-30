---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0045"
target_object: "T1564.010"
stix_relationship_id: "relationship--f62b8be5-93f7-4b69-a581-e0a991db0f87"
---
# Relationship 1666: DET0045 — detects → T1564.010

**Source object:** [[01 ATT&CK/DET0045 - Detection Strategy for Process Argument Spoofing on Windows|DET0045: Detection Strategy for Process Argument Spoofing on Windows]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1564.010 - Process Argument Spoofing|T1564.010: Process Argument Spoofing]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f62b8be5-93f7-4b69-a581-e0a991db0f87`.
