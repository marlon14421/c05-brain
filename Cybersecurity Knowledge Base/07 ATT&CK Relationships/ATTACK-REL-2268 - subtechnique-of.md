---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1127.001"
target_object: "T1127"
stix_relationship_id: "relationship--4ab2b092-a8c3-4728-9d3d-806c1ddb4796"
---
# Relationship 2268: T1127.001 — subtechnique-of → T1127

**Source object:** [[01 ATT&CK/T1127.001 - MSBuild|T1127.001: MSBuild]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1127 - Trusted Developer Utilities Proxy Execution|T1127: Trusted Developer Utilities Proxy Execution]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4ab2b092-a8c3-4728-9d3d-806c1ddb4796`.
