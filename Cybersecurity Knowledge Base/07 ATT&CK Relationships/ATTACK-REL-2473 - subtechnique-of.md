---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1127.002"
target_object: "T1127"
stix_relationship_id: "relationship--79268515-ccc0-423c-b14c-2768ff2263c9"
---
# Relationship 2473: T1127.002 — subtechnique-of → T1127

**Source object:** [[01 ATT&CK/T1127.002 - ClickOnce|T1127.002: ClickOnce]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1127 - Trusted Developer Utilities Proxy Execution|T1127: Trusted Developer Utilities Proxy Execution]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--79268515-ccc0-423c-b14c-2768ff2263c9`.
