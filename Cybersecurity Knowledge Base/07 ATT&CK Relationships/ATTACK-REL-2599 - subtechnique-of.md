---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1552.008"
target_object: "T1552"
stix_relationship_id: "relationship--c6a3ab9f-8136-4965-a765-261d95b433e6"
---
# Relationship 2599: T1552.008 — subtechnique-of → T1552

**Source object:** [[01 ATT&CK/T1552.008 - Chat Messages|T1552.008: Chat Messages]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1552 - Unsecured Credentials|T1552: Unsecured Credentials]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c6a3ab9f-8136-4965-a765-261d95b433e6`.
