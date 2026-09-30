---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0124"
target_object: "T1132.001"
stix_relationship_id: "relationship--0509ff0b-2095-466f-a6a4-72640f9a77fb"
---
# Relationship 1635: DET0124 — detects → T1132.001

**Source object:** [[01 ATT&CK/DET0124 - Behavior-chain detection for T1132.001 Data Encoding- Standard Encoding (Base64-Hex-M|DET0124: Behavior-chain detection for T1132.001 Data Encoding: Standard Encoding (Base64/Hex/MIME) across Windows, Linux, macOS, ESXi]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1132.001 - Standard Encoding|T1132.001: Standard Encoding]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0509ff0b-2095-466f-a6a4-72640f9a77fb`.
