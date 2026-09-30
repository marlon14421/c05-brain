---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0571"
target_object: "T1543"
stix_relationship_id: "relationship--f2f4bc4a-1f7a-4cb8-8635-d8461de4480c"
---
# Relationship 1961: DET0571 — detects → T1543

**Source object:** [[01 ATT&CK/DET0571 - Detection of System Process Creation or Modification Across Platforms|DET0571: Detection of System Process Creation or Modification Across Platforms]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1543 - Create or Modify System Process|T1543: Create or Modify System Process]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f2f4bc4a-1f7a-4cb8-8635-d8461de4480c`.
