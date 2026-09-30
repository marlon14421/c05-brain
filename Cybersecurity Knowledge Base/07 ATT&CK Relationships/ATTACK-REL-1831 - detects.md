---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0444"
target_object: "T1071"
stix_relationship_id: "relationship--2e32bb11-7263-46e8-b96c-c8769e7001df"
---
# Relationship 1831: DET0444 — detects → T1071

**Source object:** [[01 ATT&CK/DET0444 - Detection of Command and Control Over Application Layer Protocols|DET0444: Detection of Command and Control Over Application Layer Protocols]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1071 - Application Layer Protocol|T1071: Application Layer Protocol]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2e32bb11-7263-46e8-b96c-c8769e7001df`.
