---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1556.003"
target_object: "T1556"
stix_relationship_id: "relationship--e12a3e0d-4ed1-467b-a2f1-ead1e58b8cae"
---
# Relationship 2324: T1556.003 — subtechnique-of → T1556

**Source object:** [[01 ATT&CK/T1556.003 - Pluggable Authentication Modules|T1556.003: Pluggable Authentication Modules]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1556 - Modify Authentication Process|T1556: Modify Authentication Process]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e12a3e0d-4ed1-467b-a2f1-ead1e58b8cae`.
