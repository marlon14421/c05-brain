---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1569.001"
target_object: "T1569"
stix_relationship_id: "relationship--8d403e65-4c96-424e-9bb9-3a2eb6d66af5"
---
# Relationship 2313: T1569.001 — subtechnique-of → T1569

**Source object:** [[01 ATT&CK/T1569.001 - Launchctl|T1569.001: Launchctl]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1569 - System Services|T1569: System Services]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8d403e65-4c96-424e-9bb9-3a2eb6d66af5`.
