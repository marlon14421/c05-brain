---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0349"
target_object: "T1659"
stix_relationship_id: "relationship--622e1dcc-6185-4559-92bc-ddc6ea3c30e6"
---
# Relationship 1564: DET0349 — detects → T1659

**Source object:** [[01 ATT&CK/DET0349 - Detection Strategy for Content Injection|DET0349: Detection Strategy for Content Injection]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1659 - Content Injection|T1659: Content Injection]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--622e1dcc-6185-4559-92bc-ddc6ea3c30e6`.
