---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0320"
target_object: "T1049"
stix_relationship_id: "relationship--e287f030-f0b4-4491-b4c8-d5b5d9057e81"
---
# Relationship 1796: DET0320 — detects → T1049

**Source object:** [[01 ATT&CK/DET0320 - Detection of System Network Connections Discovery Across Platforms|DET0320: Detection of System Network Connections Discovery Across Platforms]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1049 - System Network Connections Discovery|T1049: System Network Connections Discovery]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e287f030-f0b4-4491-b4c8-d5b5d9057e81`.
