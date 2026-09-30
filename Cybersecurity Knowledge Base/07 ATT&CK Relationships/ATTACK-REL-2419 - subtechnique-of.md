---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1553.003"
target_object: "T1553"
stix_relationship_id: "relationship--b6a3348c-99db-49d0-b98e-9bc80b4cef06"
---
# Relationship 2419: T1553.003 — subtechnique-of → T1553

**Source object:** [[01 ATT&CK/T1553.003 - SIP and Trust Provider Hijacking|T1553.003: SIP and Trust Provider Hijacking]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1553 - Subvert Trust Controls|T1553: Subvert Trust Controls]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b6a3348c-99db-49d0-b98e-9bc80b4cef06`.
