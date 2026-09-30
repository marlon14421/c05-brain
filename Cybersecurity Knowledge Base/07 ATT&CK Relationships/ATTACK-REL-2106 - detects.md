---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0330"
target_object: "T1546.016"
stix_relationship_id: "relationship--62cf94f4-0a7c-465d-adfa-e982e43e84e2"
---
# Relationship 2106: DET0330 — detects → T1546.016

**Source object:** [[01 ATT&CK/DET0330 - Detection Strategy for T1546.016 - Event Triggered Execution via Installer Packages|DET0330: Detection Strategy for T1546.016 - Event Triggered Execution via Installer Packages]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1546.016 - Installer Packages|T1546.016: Installer Packages]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--62cf94f4-0a7c-465d-adfa-e982e43e84e2`.
