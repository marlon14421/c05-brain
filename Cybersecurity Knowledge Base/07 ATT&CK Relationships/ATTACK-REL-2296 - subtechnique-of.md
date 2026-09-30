---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1055.005"
target_object: "T1055"
stix_relationship_id: "relationship--4030c6bb-1f3d-4553-90d7-b984c12c5eb7"
---
# Relationship 2296: T1055.005 — subtechnique-of → T1055

**Source object:** [[01 ATT&CK/T1055.005 - Thread Local Storage|T1055.005: Thread Local Storage]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1055 - Process Injection|T1055: Process Injection]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4030c6bb-1f3d-4553-90d7-b984c12c5eb7`.
