---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1557.004"
target_object: "T1557"
stix_relationship_id: "relationship--7ad6900d-ac3a-4338-9c19-e280a8e67a8e"
---
# Relationship 2361: T1557.004 — subtechnique-of → T1557

**Source object:** [[01 ATT&CK/T1557.004 - Evil Twin|T1557.004: Evil Twin]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1557 - Adversary-in-the-Middle|T1557: Adversary-in-the-Middle]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7ad6900d-ac3a-4338-9c19-e280a8e67a8e`.
