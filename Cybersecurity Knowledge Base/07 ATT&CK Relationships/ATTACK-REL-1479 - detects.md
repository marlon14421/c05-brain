---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0255"
target_object: "T1654"
stix_relationship_id: "relationship--d47d41b9-233e-405c-99ef-e7b5592dabb3"
---
# Relationship 1479: DET0255 — detects → T1654

**Source object:** [[01 ATT&CK/DET0255 - Detection Strategy for Log Enumeration|DET0255: Detection Strategy for Log Enumeration]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1654 - Log Enumeration|T1654: Log Enumeration]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d47d41b9-233e-405c-99ef-e7b5592dabb3`.
