---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0457"
target_object: "T1095"
stix_relationship_id: "relationship--b49312bd-f37c-4b0f-a6c8-4ab38f14db65"
---
# Relationship 1579: DET0457 — detects → T1095

**Source object:** [[01 ATT&CK/DET0457 - Detection of Non-Application Layer Protocols for C2|DET0457: Detection of Non-Application Layer Protocols for C2]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1095 - Non-Application Layer Protocol|T1095: Non-Application Layer Protocol]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b49312bd-f37c-4b0f-a6c8-4ab38f14db65`.
