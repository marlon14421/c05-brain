---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1078.003"
target_object: "T1078"
stix_relationship_id: "relationship--a1a39cf1-dd69-4110-beac-77bf7acd0c62"
---
# Relationship 2454: T1078.003 — subtechnique-of → T1078

**Source object:** [[01 ATT&CK/T1078.003 - Local Accounts|T1078.003: Local Accounts]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1078 - Valid Accounts|T1078: Valid Accounts]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a1a39cf1-dd69-4110-beac-77bf7acd0c62`.
