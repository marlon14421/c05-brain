---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0441"
target_object: "T1053.005"
stix_relationship_id: "relationship--44fe6cf4-fdb3-4fa9-9855-14f3b59dc984"
---
# Relationship 2145: DET0441 — detects → T1053.005

**Source object:** [[01 ATT&CK/DET0441 - Detection of Suspicious Scheduled Task Creation and Execution on Windows|DET0441: Detection of Suspicious Scheduled Task Creation and Execution on Windows]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--44fe6cf4-fdb3-4fa9-9855-14f3b59dc984`.
