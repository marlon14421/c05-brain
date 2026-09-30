---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0575"
target_object: "T1546.007"
stix_relationship_id: "relationship--82657836-1b90-4d18-9828-1e4337fdaf37"
---
# Relationship 1650: DET0575 — detects → T1546.007

**Source object:** [[01 ATT&CK/DET0575 - Detection Strategy for Netsh Helper DLL Persistence via Registry and Child Process Mo|DET0575: Detection Strategy for Netsh Helper DLL Persistence via Registry and Child Process Monitoring (Windows)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1546.007 - Netsh Helper DLL|T1546.007: Netsh Helper DLL]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--82657836-1b90-4d18-9828-1e4337fdaf37`.
