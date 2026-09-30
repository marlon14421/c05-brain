---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1216.002"
target_object: "T1216"
stix_relationship_id: "relationship--e923fe9c-ccae-4d5a-a85c-89b398ee1ed5"
---
# Relationship 2532: T1216.002 — subtechnique-of → T1216

**Source object:** [[01 ATT&CK/T1216.002 - SyncAppvPublishingServer|T1216.002: SyncAppvPublishingServer]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1216 - System Script Proxy Execution|T1216: System Script Proxy Execution]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e923fe9c-ccae-4d5a-a85c-89b398ee1ed5`.
