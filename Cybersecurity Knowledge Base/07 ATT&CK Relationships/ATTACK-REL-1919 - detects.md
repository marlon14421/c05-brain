---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0437"
target_object: "T1003.004"
stix_relationship_id: "relationship--f09e71bc-e010-4567-8a0e-2c0ed24b5c94"
---
# Relationship 1919: DET0437 — detects → T1003.004

**Source object:** [[01 ATT&CK/DET0437 - Detection of LSA Secrets Dumping via Registry and Memory Extraction|DET0437: Detection of LSA Secrets Dumping via Registry and Memory Extraction]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1003.004 - LSA Secrets|T1003.004: LSA Secrets]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f09e71bc-e010-4567-8a0e-2c0ed24b5c94`.
