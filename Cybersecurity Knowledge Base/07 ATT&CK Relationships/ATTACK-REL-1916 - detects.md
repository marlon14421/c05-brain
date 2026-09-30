---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0498"
target_object: "T1134.003"
stix_relationship_id: "relationship--662c3c81-4b00-47d1-8110-50e7cb3e03f6"
---
# Relationship 1916: DET0498 — detects → T1134.003

**Source object:** [[01 ATT&CK/DET0498 - Behavior‑chain detection for T1134.003 Make and Impersonate Token (Windows)|DET0498: Behavior‑chain detection for T1134.003 Make and Impersonate Token (Windows)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1134.003 - Make and Impersonate Token|T1134.003: Make and Impersonate Token]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--662c3c81-4b00-47d1-8110-50e7cb3e03f6`.
