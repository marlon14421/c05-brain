---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0086"
target_object: "T1546.003"
stix_relationship_id: "relationship--93e031d7-4097-4f3e-8a4e-357c2bfc0e23"
---
# Relationship 1882: DET0086 — detects → T1546.003

**Source object:** [[01 ATT&CK/DET0086 - Detect WMI Event Subscription for Persistence via WmiPrvSE Process and MOF Compilatio|DET0086: Detect WMI Event Subscription for Persistence via WmiPrvSE Process and MOF Compilation]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1546.003 - Windows Management Instrumentation Event Subscription|T1546.003: Windows Management Instrumentation Event Subscription]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--93e031d7-4097-4f3e-8a4e-357c2bfc0e23`.
