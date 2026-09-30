---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1558.004"
target_object: "T1558"
stix_relationship_id: "relationship--f5fc2b7c-72d3-47be-8287-9608b6beb63d"
---
# Relationship 2369: T1558.004 — subtechnique-of → T1558

**Source object:** [[01 ATT&CK/T1558.004 - AS-REP Roasting|T1558.004: AS-REP Roasting]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1558 - Steal or Forge Kerberos Tickets|T1558: Steal or Forge Kerberos Tickets]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f5fc2b7c-72d3-47be-8287-9608b6beb63d`.
