---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1606.002"
target_object: "T1606"
stix_relationship_id: "relationship--847b5ffb-77a2-4892-9e96-2b454a2c3f22"
---
# Relationship 2411: T1606.002 — subtechnique-of → T1606

**Source object:** [[01 ATT&CK/T1606.002 - SAML Tokens|T1606.002: SAML Tokens]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1606 - Forge Web Credentials|T1606: Forge Web Credentials]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--847b5ffb-77a2-4892-9e96-2b454a2c3f22`.
