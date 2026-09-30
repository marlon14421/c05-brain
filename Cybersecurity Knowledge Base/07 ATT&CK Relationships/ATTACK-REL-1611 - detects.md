---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0192"
target_object: "T1564.008"
stix_relationship_id: "relationship--2f7af5f4-4ab7-48df-b228-5169033ae194"
---
# Relationship 1611: DET0192 — detects → T1564.008

**Source object:** [[01 ATT&CK/DET0192 - Detection Strategy for Email Hiding Rules|DET0192: Detection Strategy for Email Hiding Rules]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1564.008 - Email Hiding Rules|T1564.008: Email Hiding Rules]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2f7af5f4-4ab7-48df-b228-5169033ae194`.
