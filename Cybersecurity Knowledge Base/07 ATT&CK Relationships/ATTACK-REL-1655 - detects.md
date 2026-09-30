---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0038"
target_object: "T1574.005"
stix_relationship_id: "relationship--3461a5d4-6ab6-4b4b-8c3c-b1a632d09dc2"
---
# Relationship 1655: DET0038 — detects → T1574.005

**Source object:** [[01 ATT&CK/DET0038 - Detection Strategy for Hijack Execution Flow using Executable Installer File Permissi|DET0038: Detection Strategy for Hijack Execution Flow using Executable Installer File Permissions Weakness]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1574.005 - Executable Installer File Permissions Weakness|T1574.005: Executable Installer File Permissions Weakness]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3461a5d4-6ab6-4b4b-8c3c-b1a632d09dc2`.
