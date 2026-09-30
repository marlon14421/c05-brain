---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0472"
target_object: "T1556.002"
stix_relationship_id: "relationship--a19f09ed-2ca4-4b50-ac5c-1709b490ab3e"
---
# Relationship 1528: DET0472 — detects → T1556.002

**Source object:** [[01 ATT&CK/DET0472 - Detect Malicious Password Filter DLL Registration|DET0472: Detect Malicious Password Filter DLL Registration]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1556.002 - Password Filter DLL|T1556.002: Password Filter DLL]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a19f09ed-2ca4-4b50-ac5c-1709b490ab3e`.
