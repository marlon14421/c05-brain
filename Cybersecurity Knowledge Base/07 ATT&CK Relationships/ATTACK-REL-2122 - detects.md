---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0461"
target_object: "T1564.005"
stix_relationship_id: "relationship--d311635f-0633-404f-9535-51ee87662507"
---
# Relationship 2122: DET0461 — detects → T1564.005

**Source object:** [[01 ATT&CK/DET0461 - Detection Strategy for Hidden File System Abuse|DET0461: Detection Strategy for Hidden File System Abuse]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1564.005 - Hidden File System|T1564.005: Hidden File System]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d311635f-0633-404f-9535-51ee87662507`.
