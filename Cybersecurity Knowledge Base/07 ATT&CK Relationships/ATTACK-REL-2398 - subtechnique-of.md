---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1601.001"
target_object: "T1601"
stix_relationship_id: "relationship--fca5a1c7-8548-4621-97b5-023572344ae4"
---
# Relationship 2398: T1601.001 — subtechnique-of → T1601

**Source object:** [[01 ATT&CK/T1601.001 - Patch System Image|T1601.001: Patch System Image]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1601 - Modify System Image|T1601: Modify System Image]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fca5a1c7-8548-4621-97b5-023572344ae4`.
