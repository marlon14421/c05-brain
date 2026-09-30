---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1556.009"
target_object: "T1556"
stix_relationship_id: "relationship--38ae2a97-1756-4452-b542-33d00b891742"
---
# Relationship 2346: T1556.009 — subtechnique-of → T1556

**Source object:** [[01 ATT&CK/T1556.009 - Conditional Access Policies|T1556.009: Conditional Access Policies]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1556 - Modify Authentication Process|T1556: Modify Authentication Process]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--38ae2a97-1756-4452-b542-33d00b891742`.
