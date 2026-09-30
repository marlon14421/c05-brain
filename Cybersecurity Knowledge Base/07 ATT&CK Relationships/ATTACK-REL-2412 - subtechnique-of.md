---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1558.003"
target_object: "T1558"
stix_relationship_id: "relationship--944b9cc3-95c7-4e0d-8b62-576aa6cf7217"
---
# Relationship 2412: T1558.003 — subtechnique-of → T1558

**Source object:** [[01 ATT&CK/T1558.003 - Kerberoasting|T1558.003: Kerberoasting]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1558 - Steal or Forge Kerberos Tickets|T1558: Steal or Forge Kerberos Tickets]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--944b9cc3-95c7-4e0d-8b62-576aa6cf7217`.
