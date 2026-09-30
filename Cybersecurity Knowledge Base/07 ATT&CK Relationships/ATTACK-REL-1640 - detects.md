---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0807"
target_object: "T1591.004"
stix_relationship_id: "relationship--eb3fef47-ca5c-4a84-861b-b51feabfc738"
---
# Relationship 1640: DET0807 — detects → T1591.004

**Source object:** [[01 ATT&CK/DET0807 - Detection of Identify Roles|DET0807: Detection of Identify Roles]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1591.004 - Identify Roles|T1591.004: Identify Roles]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--eb3fef47-ca5c-4a84-861b-b51feabfc738`.
