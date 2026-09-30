---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1036.007"
target_object: "T1036"
stix_relationship_id: "relationship--8dda1296-0835-4748-92a3-24b34eb8a084"
---
# Relationship 2304: T1036.007 — subtechnique-of → T1036

**Source object:** [[01 ATT&CK/T1036.007 - Double File Extension|T1036.007: Double File Extension]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1036 - Masquerading|T1036: Masquerading]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8dda1296-0835-4748-92a3-24b34eb8a084`.
