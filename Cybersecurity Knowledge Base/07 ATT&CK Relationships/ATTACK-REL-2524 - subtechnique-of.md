---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1546.017"
target_object: "T1546"
stix_relationship_id: "relationship--ce460e6d-9c29-4b1d-8a46-e4af52c9805c"
---
# Relationship 2524: T1546.017 — subtechnique-of → T1546

**Source object:** [[01 ATT&CK/T1546.017 - Udev Rules|T1546.017: Udev Rules]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1546 - Event Triggered Execution|T1546: Event Triggered Execution]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ce460e6d-9c29-4b1d-8a46-e4af52c9805c`.
