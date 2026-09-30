---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0450"
target_object: "T1547.006"
stix_relationship_id: "relationship--0fd967ee-9c2d-45ef-acfb-61ac5a909eaa"
---
# Relationship 1704: DET0450 — detects → T1547.006

**Source object:** [[01 ATT&CK/DET0450 - Detection Strategy for Kernel Modules and Extensions Autostart Execution|DET0450: Detection Strategy for Kernel Modules and Extensions Autostart Execution]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1547.006 - Kernel Modules and Extensions|T1547.006: Kernel Modules and Extensions]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0fd967ee-9c2d-45ef-acfb-61ac5a909eaa`.
