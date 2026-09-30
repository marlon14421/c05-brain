---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0291"
target_object: "T1538"
stix_relationship_id: "relationship--3773ce57-ad3c-47ae-8484-6a42338dddf4"
---
# Relationship 2015: DET0291 — detects → T1538

**Source object:** [[01 ATT&CK/DET0291 - Detection of Cloud Service Dashboard Usage via GUI-Based Cloud Access|DET0291: Detection of Cloud Service Dashboard Usage via GUI-Based Cloud Access]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1538 - Cloud Service Dashboard|T1538: Cloud Service Dashboard]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3773ce57-ad3c-47ae-8484-6a42338dddf4`.
