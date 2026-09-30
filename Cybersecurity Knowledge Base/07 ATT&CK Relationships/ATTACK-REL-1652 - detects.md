---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0076"
target_object: "T1059.005"
stix_relationship_id: "relationship--0700bc4e-dc25-46d5-9ad0-4c64c7a46fbc"
---
# Relationship 1652: DET0076 — detects → T1059.005

**Source object:** [[01 ATT&CK/DET0076 - Behavioral Detection of Visual Basic Execution (VBS-VBA-VBScript)|DET0076: Behavioral Detection of Visual Basic Execution (VBS/VBA/VBScript)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1059.005 - Visual Basic|T1059.005: Visual Basic]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0700bc4e-dc25-46d5-9ad0-4c64c7a46fbc`.
