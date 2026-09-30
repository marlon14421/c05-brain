---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0264"
target_object: "T1059.007"
stix_relationship_id: "relationship--04ec88c4-d2a0-4d1a-ab06-068dd78fad09"
---
# Relationship 1805: DET0264 — detects → T1059.007

**Source object:** [[01 ATT&CK/DET0264 - Cross-Platform Detection of JavaScript Execution Abuse|DET0264: Cross-Platform Detection of JavaScript Execution Abuse]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1059.007 - JavaScript|T1059.007: JavaScript]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--04ec88c4-d2a0-4d1a-ab06-068dd78fad09`.
