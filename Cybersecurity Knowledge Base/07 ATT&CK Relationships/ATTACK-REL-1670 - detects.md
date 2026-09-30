---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0218"
target_object: "T1574"
stix_relationship_id: "relationship--978cce2b-4185-4d79-87c9-4754712b5623"
---
# Relationship 1670: DET0218 — detects → T1574

**Source object:** [[01 ATT&CK/DET0218 - Detection Strategy for Hijack Execution Flow across OS platforms|DET0218: Detection Strategy for Hijack Execution Flow across OS platforms.]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1574 - Hijack Execution Flow|T1574: Hijack Execution Flow]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--978cce2b-4185-4d79-87c9-4754712b5623`.
