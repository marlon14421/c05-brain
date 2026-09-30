---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0899"
target_object: "T1684"
stix_relationship_id: "relationship--88a3f8a5-5518-4c0f-b0d6-3ea73df46eea"
---
# Relationship 1591: DET0899 — detects → T1684

**Source object:** [[01 ATT&CK/DET0899 - Detect Social Engineering|DET0899: Detect Social Engineering]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1684 - Social Engineering|T1684: Social Engineering]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--88a3f8a5-5518-4c0f-b0d6-3ea73df46eea`.
