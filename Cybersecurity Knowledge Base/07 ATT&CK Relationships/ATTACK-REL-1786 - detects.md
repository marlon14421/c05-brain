---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0379"
target_object: "T1557.004"
stix_relationship_id: "relationship--e8d124c9-f162-4c7e-aadd-c50476b22cd7"
---
# Relationship 1786: DET0379 — detects → T1557.004

**Source object:** [[01 ATT&CK/DET0379 - Detect Evil Twin Wi-Fi Access Points on Network Devices|DET0379: Detect Evil Twin Wi-Fi Access Points on Network Devices]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1557.004 - Evil Twin|T1557.004: Evil Twin]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e8d124c9-f162-4c7e-aadd-c50476b22cd7`.
