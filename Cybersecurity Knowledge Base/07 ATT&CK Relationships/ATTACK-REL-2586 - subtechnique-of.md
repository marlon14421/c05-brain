---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1213.004"
target_object: "T1213"
stix_relationship_id: "relationship--a8a181e0-74b8-42e2-96c7-a75e57cbb2fe"
---
# Relationship 2586: T1213.004 — subtechnique-of → T1213

**Source object:** [[01 ATT&CK/T1213.004 - Customer Relationship Management Software|T1213.004: Customer Relationship Management Software]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1213 - Data from Information Repositories|T1213: Data from Information Repositories]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a8a181e0-74b8-42e2-96c7-a75e57cbb2fe`.
