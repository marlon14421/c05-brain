---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0174"
target_object: "T1212"
stix_relationship_id: "relationship--dd04f99b-5d2b-4e1c-a4e5-3f48aaea895d"
---
# Relationship 1904: DET0174 — detects → T1212

**Source object:** [[01 ATT&CK/DET0174 - Detection Strategy for Exploitation for Credential Access|DET0174: Detection Strategy for Exploitation for Credential Access]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1212 - Exploitation for Credential Access|T1212: Exploitation for Credential Access]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dd04f99b-5d2b-4e1c-a4e5-3f48aaea895d`.
