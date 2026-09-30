---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0453"
target_object: "T1602.001"
stix_relationship_id: "relationship--8b80bbc6-57c9-41b1-93cd-2bd2ae433f4f"
---
# Relationship 2077: DET0453 — detects → T1602.001

**Source object:** [[01 ATT&CK/DET0453 - Detection Strategy for SNMP (MIB Dump) on Network Devices|DET0453: Detection Strategy for SNMP (MIB Dump) on Network Devices]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1602.001 - SNMP (MIB Dump)|T1602.001: SNMP (MIB Dump)]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8b80bbc6-57c9-41b1-93cd-2bd2ae433f4f`.
