---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1053.005"
target_object: "T1053"
stix_relationship_id: "relationship--d5ffcd6e-be9e-4efe-9822-974f3838c7db"
---
# Relationship 2507: T1053.005 — subtechnique-of → T1053

**Source object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1053 - Scheduled Task-Job|T1053: Scheduled Task/Job]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d5ffcd6e-be9e-4efe-9822-974f3838c7db`.
