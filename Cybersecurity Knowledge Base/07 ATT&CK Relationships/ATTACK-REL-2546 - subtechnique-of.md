---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1090.002"
target_object: "T1090"
stix_relationship_id: "relationship--3d16dbff-d1fc-42e0-b736-69ddee747ffe"
---
# Relationship 2546: T1090.002 — subtechnique-of → T1090

**Source object:** [[01 ATT&CK/T1090.002 - External Proxy|T1090.002: External Proxy]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1090 - Proxy|T1090: Proxy]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3d16dbff-d1fc-42e0-b736-69ddee747ffe`.
