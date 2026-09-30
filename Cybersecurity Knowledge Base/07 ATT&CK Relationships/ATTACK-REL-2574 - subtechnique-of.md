---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1222.002"
target_object: "T1222"
stix_relationship_id: "relationship--1eb067c7-e741-46b6-9080-dbc8395f8c43"
---
# Relationship 2574: T1222.002 — subtechnique-of → T1222

**Source object:** [[01 ATT&CK/T1222.002 - Linux and Mac Permissions|T1222.002: Linux and Mac Permissions]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1222 - File and Directory Permissions Modification|T1222: File and Directory Permissions Modification]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1eb067c7-e741-46b6-9080-dbc8395f8c43`.
