---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1069.001"
target_object: "T1069"
stix_relationship_id: "relationship--6b46c35d-aa25-430c-89a2-d8f512478122"
---
# Relationship 2198: T1069.001 — subtechnique-of → T1069

**Source object:** [[01 ATT&CK/T1069.001 - Local Groups|T1069.001: Local Groups]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1069 - Permission Groups Discovery|T1069: Permission Groups Discovery]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6b46c35d-aa25-430c-89a2-d8f512478122`.
