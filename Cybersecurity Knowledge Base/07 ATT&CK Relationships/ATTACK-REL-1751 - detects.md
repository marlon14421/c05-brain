---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0516"
target_object: "T1059"
stix_relationship_id: "relationship--51b6dafa-da43-4f59-aea4-30caa3a10005"
---
# Relationship 1751: DET0516 — detects → T1059

**Source object:** [[01 ATT&CK/DET0516 - Behavioral Detection of Command and Scripting Interpreter Abuse|DET0516: Behavioral Detection of Command and Scripting Interpreter Abuse]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1059 - Command and Scripting Interpreter|T1059: Command and Scripting Interpreter]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--51b6dafa-da43-4f59-aea4-30caa3a10005`.
