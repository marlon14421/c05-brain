---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0580"
target_object: "T1556.008"
stix_relationship_id: "relationship--f80b62c3-bab4-4c50-b725-1e49c90961bf"
---
# Relationship 2080: DET0580 — detects → T1556.008

**Source object:** [[01 ATT&CK/DET0580 - Detect Network Provider DLL Registration and Credential Capture|DET0580: Detect Network Provider DLL Registration and Credential Capture]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1556.008 - Network Provider DLL|T1556.008: Network Provider DLL]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f80b62c3-bab4-4c50-b725-1e49c90961bf`.
