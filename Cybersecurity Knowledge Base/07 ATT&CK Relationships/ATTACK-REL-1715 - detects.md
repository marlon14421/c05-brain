---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0283"
target_object: "T1134"
stix_relationship_id: "relationship--d4efc88e-7544-42f4-ae47-a73acc22885a"
---
# Relationship 1715: DET0283 — detects → T1134

**Source object:** [[01 ATT&CK/DET0283 - Behavior-chain detection for T1134 Access Token Manipulation on Windows|DET0283: Behavior-chain detection for T1134 Access Token Manipulation on Windows]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1134 - Access Token Manipulation|T1134: Access Token Manipulation]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d4efc88e-7544-42f4-ae47-a73acc22885a`.
