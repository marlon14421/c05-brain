---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0897"
target_object: "T1679"
stix_relationship_id: "relationship--e7512377-4cb8-4552-97d6-518038b765f7"
---
# Relationship 1981: DET0897 — detects → T1679

**Source object:** [[01 ATT&CK/DET0897 - Detection of Selective Exclusion|DET0897: Detection of Selective Exclusion]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1679 - Selective Exclusion|T1679: Selective Exclusion]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e7512377-4cb8-4552-97d6-518038b765f7`.
