---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0436"
target_object: "T1574.010"
stix_relationship_id: "relationship--5346102a-9994-4eb2-ab3e-b430fe4f6c67"
---
# Relationship 1654: DET0436 — detects → T1574.010

**Source object:** [[01 ATT&CK/DET0436 - Detection Strategy for Hijack Execution Flow through Services File Permissions Weakne|DET0436: Detection Strategy for Hijack Execution Flow through Services File Permissions Weakness.]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1574.010 - Services File Permissions Weakness|T1574.010: Services File Permissions Weakness]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5346102a-9994-4eb2-ab3e-b430fe4f6c67`.
