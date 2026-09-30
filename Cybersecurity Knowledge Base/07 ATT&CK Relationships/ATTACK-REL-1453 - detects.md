---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0377"
target_object: "T1014"
stix_relationship_id: "relationship--13f0f64f-c275-48dc-8fb3-dda48df60d8c"
---
# Relationship 1453: DET0377 — detects → T1014

**Source object:** [[01 ATT&CK/DET0377 - Detection of Kernel-User-Level Rootkit Behavior Across Platforms|DET0377: Detection of Kernel/User-Level Rootkit Behavior Across Platforms]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1014 - Rootkit|T1014: Rootkit]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--13f0f64f-c275-48dc-8fb3-dda48df60d8c`.
