---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0475"
target_object: "T1218.011"
stix_relationship_id: "relationship--3b6dd089-2818-4717-9956-8829fe08f252"
---
# Relationship 1656: DET0475 — detects → T1218.011

**Source object:** [[01 ATT&CK/DET0475 - Detection Strategy for T1218.011 Rundll32 Abuse|DET0475: Detection Strategy for T1218.011 Rundll32 Abuse]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1218.011 - Rundll32|T1218.011: Rundll32]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3b6dd089-2818-4717-9956-8829fe08f252`.
