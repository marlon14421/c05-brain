---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1593.002"
target_object: "T1593"
stix_relationship_id: "relationship--3be9d897-5a20-4e2f-8b73-2a69256925b0"
---
# Relationship 2378: T1593.002 — subtechnique-of → T1593

**Source object:** [[01 ATT&CK/T1593.002 - Search Engines|T1593.002: Search Engines]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1593 - Search Open Websites-Domains|T1593: Search Open Websites/Domains]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3be9d897-5a20-4e2f-8b73-2a69256925b0`.
