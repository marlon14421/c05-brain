---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0313"
target_object: "T1027.006"
stix_relationship_id: "relationship--a1177021-bbf1-4208-a1c3-de76bafb687d"
---
# Relationship 2142: DET0313 — detects → T1027.006

**Source object:** [[01 ATT&CK/DET0313 - Detection Strategy for HTML Smuggling via JavaScript Blob + Dynamic File Drop|DET0313: Detection Strategy for HTML Smuggling via JavaScript Blob + Dynamic File Drop]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1027.006 - HTML Smuggling|T1027.006: HTML Smuggling]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a1177021-bbf1-4208-a1c3-de76bafb687d`.
