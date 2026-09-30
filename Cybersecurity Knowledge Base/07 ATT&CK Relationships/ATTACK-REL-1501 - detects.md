---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0279"
target_object: "T1569"
stix_relationship_id: "relationship--20cd9b34-087b-42ab-9819-fe330c06c89d"
---
# Relationship 1501: DET0279 — detects → T1569

**Source object:** [[01 ATT&CK/DET0279 - Detection Strategy for System Services across OS platforms|DET0279: Detection Strategy for System Services across OS platforms.]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1569 - System Services|T1569: System Services]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--20cd9b34-087b-42ab-9819-fe330c06c89d`.
