---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0168"
target_object: "T1497.001"
stix_relationship_id: "relationship--327decec-03ad-41da-a251-fcbd1f485c24"
---
# Relationship 1660: DET0168 — detects → T1497.001

**Source object:** [[01 ATT&CK/DET0168 - Virtualization-Sandbox Evasion via System Checks across Windows, Linux, macOS|DET0168: Virtualization/Sandbox Evasion via System Checks across Windows, Linux, macOS]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1497.001 - System Checks|T1497.001: System Checks]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--327decec-03ad-41da-a251-fcbd1f485c24`.
