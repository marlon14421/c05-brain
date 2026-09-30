---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0267"
target_object: "T1496"
stix_relationship_id: "relationship--c267dfc4-92f8-41f5-a101-177153e674c3"
---
# Relationship 1546: DET0267 — detects → T1496

**Source object:** [[01 ATT&CK/DET0267 - Resource Hijacking Detection Strategy|DET0267: Resource Hijacking Detection Strategy]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1496 - Resource Hijacking|T1496: Resource Hijacking]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c267dfc4-92f8-41f5-a101-177153e674c3`.
