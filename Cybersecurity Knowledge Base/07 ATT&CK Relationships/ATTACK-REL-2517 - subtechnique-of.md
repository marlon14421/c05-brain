---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1550.002"
target_object: "T1550"
stix_relationship_id: "relationship--c54ccdc7-ed15-45c7-bfc9-f6e6e2b0d7f3"
---
# Relationship 2517: T1550.002 — subtechnique-of → T1550

**Source object:** [[01 ATT&CK/T1550.002 - Pass the Hash|T1550.002: Pass the Hash]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1550 - Use Alternate Authentication Material|T1550: Use Alternate Authentication Material]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c54ccdc7-ed15-45c7-bfc9-f6e6e2b0d7f3`.
