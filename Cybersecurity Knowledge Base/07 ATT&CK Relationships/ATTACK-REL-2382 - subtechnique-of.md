---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1204.002"
target_object: "T1204"
stix_relationship_id: "relationship--b2d97276-503d-4fd0-9517-92e05a774de0"
---
# Relationship 2382: T1204.002 — subtechnique-of → T1204

**Source object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1204 - User Execution|T1204: User Execution]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b2d97276-503d-4fd0-9517-92e05a774de0`.
