---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1055.002"
target_object: "T1055"
stix_relationship_id: "relationship--fc26d209-c7fb-4d59-82da-0be7c72c651d"
---
# Relationship 2397: T1055.002 — subtechnique-of → T1055

**Source object:** [[01 ATT&CK/T1055.002 - Portable Executable Injection|T1055.002: Portable Executable Injection]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1055 - Process Injection|T1055: Process Injection]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fc26d209-c7fb-4d59-82da-0be7c72c651d`.
