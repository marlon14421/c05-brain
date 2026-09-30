---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0012"
target_object: "T1564.007"
stix_relationship_id: "relationship--15d4e0ff-17f8-44f1-8f01-167dcad0e288"
---
# Relationship 2056: DET0012 — detects → T1564.007

**Source object:** [[01 ATT&CK/DET0012 - Detection Strategy for VBA Stomping|DET0012: Detection Strategy for VBA Stomping]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1564.007 - VBA Stomping|T1564.007: VBA Stomping]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--15d4e0ff-17f8-44f1-8f01-167dcad0e288`.
