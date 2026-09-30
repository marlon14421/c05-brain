---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0533"
target_object: "T1677"
stix_relationship_id: "relationship--ce76daca-413c-4075-9ca2-84a1ca1fbc93"
---
# Relationship 2111: DET0533 — detects → T1677

**Source object:** [[01 ATT&CK/DET0533 - Detection Strategy for Poisoned Pipeline Execution via SaaS CI-CD Workflows|DET0533: Detection Strategy for Poisoned Pipeline Execution via SaaS CI/CD Workflows]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1677 - Poisoned Pipeline Execution|T1677: Poisoned Pipeline Execution]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ce76daca-413c-4075-9ca2-84a1ca1fbc93`.
