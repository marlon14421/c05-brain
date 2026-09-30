---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1574.011"
target_object: "T1574"
stix_relationship_id: "relationship--def869f4-7564-4a09-8f49-59cb696b660d"
---
# Relationship 2474: T1574.011 — subtechnique-of → T1574

**Source object:** [[01 ATT&CK/T1574.011 - Services Registry Permissions Weakness|T1574.011: Services Registry Permissions Weakness]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1574 - Hijack Execution Flow|T1574: Hijack Execution Flow]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--def869f4-7564-4a09-8f49-59cb696b660d`.
