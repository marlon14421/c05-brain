---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1098.007"
target_object: "T1098"
stix_relationship_id: "relationship--d226c16d-ffb6-4a47-a5f1-7e1183b6c030"
---
# Relationship 2345: T1098.007 — subtechnique-of → T1098

**Source object:** [[01 ATT&CK/T1098.007 - Additional Local or Domain Groups|T1098.007: Additional Local or Domain Groups]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1098 - Account Manipulation|T1098: Account Manipulation]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d226c16d-ffb6-4a47-a5f1-7e1183b6c030`.
