---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0156"
target_object: "T1496.003"
stix_relationship_id: "relationship--3c88d345-0f5d-4b12-98d6-3fdb32f9aae7"
---
# Relationship 1757: DET0156 — detects → T1496.003

**Source object:** [[01 ATT&CK/DET0156 - Detection Strategy for Resource Hijacking- SMS Pumping via SaaS Application Logs|DET0156: Detection Strategy for Resource Hijacking: SMS Pumping via SaaS Application Logs]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1496.003 - SMS Pumping|T1496.003: SMS Pumping]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3c88d345-0f5d-4b12-98d6-3fdb32f9aae7`.
