---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0568"
target_object: "T1674"
stix_relationship_id: "relationship--dab158f6-c216-43d6-8c8c-f20d76d6206f"
---
# Relationship 1885: DET0568 — detects → T1674

**Source object:** [[01 ATT&CK/DET0568 - Detection Strategy for Input Injection|DET0568: Detection Strategy for Input Injection]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1674 - Input Injection|T1674: Input Injection]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dab158f6-c216-43d6-8c8c-f20d76d6206f`.
