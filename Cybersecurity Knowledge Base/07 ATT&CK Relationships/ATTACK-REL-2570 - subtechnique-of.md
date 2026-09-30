---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1505.003"
target_object: "T1505"
stix_relationship_id: "relationship--b5963cc5-0488-46a8-b47a-b781ac724590"
---
# Relationship 2570: T1505.003 — subtechnique-of → T1505

**Source object:** [[01 ATT&CK/T1505.003 - Web Shell|T1505.003: Web Shell]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1505 - Server Software Component|T1505: Server Software Component]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b5963cc5-0488-46a8-b47a-b781ac724590`.
