---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1560.003"
target_object: "T1560"
stix_relationship_id: "relationship--e2980209-0a3b-4d12-8a85-1984b8e1844b"
---
# Relationship 2229: T1560.003 — subtechnique-of → T1560

**Source object:** [[01 ATT&CK/T1560.003 - Archive via Custom Method|T1560.003: Archive via Custom Method]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1560 - Archive Collected Data|T1560: Archive Collected Data]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e2980209-0a3b-4d12-8a85-1984b8e1844b`.
