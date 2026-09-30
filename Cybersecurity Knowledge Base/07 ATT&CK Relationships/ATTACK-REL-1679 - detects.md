---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0816"
target_object: "T1597.001"
stix_relationship_id: "relationship--45c4401a-c104-4f80-93e1-bf8d64ed9711"
---
# Relationship 1679: DET0816 — detects → T1597.001

**Source object:** [[01 ATT&CK/DET0816 - Detection of Threat Intel Vendors|DET0816: Detection of Threat Intel Vendors]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1597.001 - Threat Intel Vendors|T1597.001: Threat Intel Vendors]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--45c4401a-c104-4f80-93e1-bf8d64ed9711`.
