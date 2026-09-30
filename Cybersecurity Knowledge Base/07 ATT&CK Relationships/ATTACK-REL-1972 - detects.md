---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0489"
target_object: "T1134.004"
stix_relationship_id: "relationship--b950ec4c-7d64-4184-9161-bcc199117ed2"
---
# Relationship 1972: DET0489 — detects → T1134.004

**Source object:** [[01 ATT&CK/DET0489 - Behavior-chain detection for T1134.004 Access Token Manipulation- Parent PID Spoofing|DET0489: Behavior-chain detection for T1134.004 Access Token Manipulation: Parent PID Spoofing (Windows)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1134.004 - Parent PID Spoofing|T1134.004: Parent PID Spoofing]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b950ec4c-7d64-4184-9161-bcc199117ed2`.
