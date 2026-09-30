---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0326"
target_object: "T1132.002"
stix_relationship_id: "relationship--488d1ba3-25ca-4a0c-b0b6-1d8053ce5cd3"
---
# Relationship 1997: DET0326 — detects → T1132.002

**Source object:** [[01 ATT&CK/DET0326 - Behavior-chain detection for T1132.002 Data Encoding- Non-Standard Encoding across Wi|DET0326: Behavior-chain detection for T1132.002 Data Encoding: Non-Standard Encoding across Windows, Linux, macOS, ESXi]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1132.002 - Non-Standard Encoding|T1132.002: Non-Standard Encoding]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--488d1ba3-25ca-4a0c-b0b6-1d8053ce5cd3`.
