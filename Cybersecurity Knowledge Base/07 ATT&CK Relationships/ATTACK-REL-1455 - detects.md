---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0481"
target_object: "T1546.015"
stix_relationship_id: "relationship--f779a804-fdd3-4bf3-a0bb-2e1c4d2ab31f"
---
# Relationship 1455: DET0481 — detects → T1546.015

**Source object:** [[01 ATT&CK/DET0481 - Windows COM Hijacking Detection via Registry and DLL Load Correlation|DET0481: Windows COM Hijacking Detection via Registry and DLL Load Correlation]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1546.015 - Component Object Model Hijacking|T1546.015: Component Object Model Hijacking]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f779a804-fdd3-4bf3-a0bb-2e1c4d2ab31f`.
