---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0452"
target_object: "T1553"
stix_relationship_id: "relationship--9e91959a-a90f-4523-8ad3-8b713a919656"
---
# Relationship 1529: DET0452 — detects → T1553

**Source object:** [[01 ATT&CK/DET0452 - Detect Subversion of Trust Controls via Certificate, Registry, and Attribute Manipula|DET0452: Detect Subversion of Trust Controls via Certificate, Registry, and Attribute Manipulation]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1553 - Subvert Trust Controls|T1553: Subvert Trust Controls]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9e91959a-a90f-4523-8ad3-8b713a919656`.
