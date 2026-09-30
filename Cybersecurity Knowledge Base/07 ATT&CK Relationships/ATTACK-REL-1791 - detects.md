---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0010"
target_object: "T1546"
stix_relationship_id: "relationship--e6a8c456-3c2e-44a6-8614-b5c3e7cb4d98"
---
# Relationship 1791: DET0010 — detects → T1546

**Source object:** [[01 ATT&CK/DET0010 - Behavioral Detection of Event Triggered Execution Across Platforms|DET0010: Behavioral Detection of Event Triggered Execution Across Platforms]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1546 - Event Triggered Execution|T1546: Event Triggered Execution]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e6a8c456-3c2e-44a6-8614-b5c3e7cb4d98`.
