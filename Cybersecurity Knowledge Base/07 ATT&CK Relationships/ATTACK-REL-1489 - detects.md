---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0104"
target_object: "T1556"
stix_relationship_id: "relationship--d071af46-206b-4ad4-994a-a4ffb350676e"
---
# Relationship 1489: DET0104 — detects → T1556

**Source object:** [[01 ATT&CK/DET0104 - Detect Modification of Authentication Processes Across Platforms|DET0104: Detect Modification of Authentication Processes Across Platforms]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1556 - Modify Authentication Process|T1556: Modify Authentication Process]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d071af46-206b-4ad4-994a-a4ffb350676e`.
