---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0386"
target_object: "T1087.004"
stix_relationship_id: "relationship--4804e967-8bec-4016-ac4c-fc697216d445"
---
# Relationship 1505: DET0386 — detects → T1087.004

**Source object:** [[01 ATT&CK/DET0386 - Cloud Account Enumeration via API, CLI, and Scripting Interfaces|DET0386: Cloud Account Enumeration via API, CLI, and Scripting Interfaces]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1087.004 - Cloud Account|T1087.004: Cloud Account]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4804e967-8bec-4016-ac4c-fc697216d445`.
