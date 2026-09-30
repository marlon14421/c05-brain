---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1497.001"
target_object: "T1497"
stix_relationship_id: "relationship--9ba97a0a-1ae5-4969-9ce4-6fb86d70fae0"
---
# Relationship 2390: T1497.001 — subtechnique-of → T1497

**Source object:** [[01 ATT&CK/T1497.001 - System Checks|T1497.001: System Checks]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1497 - Virtualization-Sandbox Evasion|T1497: Virtualization/Sandbox Evasion]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9ba97a0a-1ae5-4969-9ce4-6fb86d70fae0`.
