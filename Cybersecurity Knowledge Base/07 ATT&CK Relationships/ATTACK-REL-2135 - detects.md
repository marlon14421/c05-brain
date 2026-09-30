---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0382"
target_object: "T1055.012"
stix_relationship_id: "relationship--d9f348c1-07b1-4230-ac20-cb91b2944020"
---
# Relationship 2135: DET0382 — detects → T1055.012

**Source object:** [[01 ATT&CK/DET0382 - Detection Strategy for Process Hollowing on Windows|DET0382: Detection Strategy for Process Hollowing on Windows]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1055.012 - Process Hollowing|T1055.012: Process Hollowing]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d9f348c1-07b1-4230-ac20-cb91b2944020`.
