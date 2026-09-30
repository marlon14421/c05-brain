---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1001.001"
target_object: "T1001"
stix_relationship_id: "relationship--38c7e0b8-3961-48ed-b5e6-c4763c212ecb"
---
# Relationship 2610: T1001.001 — subtechnique-of → T1001

**Source object:** [[01 ATT&CK/T1001.001 - Junk Data|T1001.001: Junk Data]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1001 - Data Obfuscation|T1001: Data Obfuscation]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--38c7e0b8-3961-48ed-b5e6-c4763c212ecb`.
