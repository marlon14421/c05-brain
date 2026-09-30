---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0079"
target_object: "T1563"
stix_relationship_id: "relationship--91aad2e7-a865-4f83-88c8-c844822f3d81"
---
# Relationship 2123: DET0079 — detects → T1563

**Source object:** [[01 ATT&CK/DET0079 - Detection of Remote Service Session Hijacking|DET0079: Detection of Remote Service Session Hijacking]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1563 - Remote Service Session Hijacking|T1563: Remote Service Session Hijacking]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--91aad2e7-a865-4f83-88c8-c844822f3d81`.
