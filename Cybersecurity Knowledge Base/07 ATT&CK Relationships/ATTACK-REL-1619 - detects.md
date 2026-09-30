---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0588"
target_object: "T1563.002"
stix_relationship_id: "relationship--29016afa-0769-41ea-ba47-9f4aecf6228d"
---
# Relationship 1619: DET0588 — detects → T1563.002

**Source object:** [[01 ATT&CK/DET0588 - Detection of Remote Service Session Hijacking for RDP|DET0588: Detection of Remote Service Session Hijacking for RDP.]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1563.002 - RDP Hijacking|T1563.002: RDP Hijacking]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--29016afa-0769-41ea-ba47-9f4aecf6228d`.
