---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1574.009"
target_object: "T1574"
stix_relationship_id: "relationship--a6f0c9d2-ae40-4dee-9231-4f6fa3d87b00"
---
# Relationship 2294: T1574.009 — subtechnique-of → T1574

**Source object:** [[01 ATT&CK/T1574.009 - Path Interception by Unquoted Path|T1574.009: Path Interception by Unquoted Path]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1574 - Hijack Execution Flow|T1574: Hijack Execution Flow]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a6f0c9d2-ae40-4dee-9231-4f6fa3d87b00`.
