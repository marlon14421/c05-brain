---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0272"
target_object: "T1556.004"
stix_relationship_id: "relationship--21d51911-648d-4d48-b0e4-52dcbb639c8c"
---
# Relationship 1978: DET0272 — detects → T1556.004

**Source object:** [[01 ATT&CK/DET0272 - Detect Modification of Network Device Authentication via Patched System Images|DET0272: Detect Modification of Network Device Authentication via Patched System Images]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1556.004 - Network Device Authentication|T1556.004: Network Device Authentication]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--21d51911-648d-4d48-b0e4-52dcbb639c8c`.
