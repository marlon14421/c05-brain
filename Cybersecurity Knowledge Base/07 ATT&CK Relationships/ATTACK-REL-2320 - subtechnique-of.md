---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1542.004"
target_object: "T1542"
stix_relationship_id: "relationship--e07acc2b-6a92-423e-85be-a9caed4a8ee6"
---
# Relationship 2320: T1542.004 — subtechnique-of → T1542

**Source object:** [[01 ATT&CK/T1542.004 - ROMMONkit|T1542.004: ROMMONkit]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1542 - Pre-OS Boot|T1542: Pre-OS Boot]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e07acc2b-6a92-423e-85be-a9caed4a8ee6`.
