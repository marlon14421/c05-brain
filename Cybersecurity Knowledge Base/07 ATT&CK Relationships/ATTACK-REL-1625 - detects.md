---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0243"
target_object: "T1600.001"
stix_relationship_id: "relationship--04a5acf8-e348-427d-868b-e5a35a1e9880"
---
# Relationship 1625: DET0243 — detects → T1600.001

**Source object:** [[01 ATT&CK/DET0243 - Detection Strategy for Weaken Encryption- Reduce Key Space on Network Devices|DET0243: Detection Strategy for Weaken Encryption: Reduce Key Space on Network Devices]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1600.001 - Reduce Key Space|T1600.001: Reduce Key Space]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--04a5acf8-e348-427d-868b-e5a35a1e9880`.
