---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0346"
target_object: "T1113"
stix_relationship_id: "relationship--2e10339a-3af5-45b5-b48c-9642e4bc7665"
---
# Relationship 1934: DET0346 — detects → T1113

**Source object:** [[01 ATT&CK/DET0346 - Detect Screen Capture via Commands and API Calls|DET0346: Detect Screen Capture via Commands and API Calls]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2e10339a-3af5-45b5-b48c-9642e4bc7665`.
