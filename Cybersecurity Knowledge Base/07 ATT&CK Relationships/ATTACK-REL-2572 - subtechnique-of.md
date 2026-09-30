---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1564.011"
target_object: "T1564"
stix_relationship_id: "relationship--30a29f1a-41ec-4cf2-8d47-07c03c2d96e0"
---
# Relationship 2572: T1564.011 — subtechnique-of → T1564

**Source object:** [[01 ATT&CK/T1564.011 - Ignore Process Interrupts|T1564.011: Ignore Process Interrupts]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1564 - Hide Artifacts|T1564: Hide Artifacts]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--30a29f1a-41ec-4cf2-8d47-07c03c2d96e0`.
