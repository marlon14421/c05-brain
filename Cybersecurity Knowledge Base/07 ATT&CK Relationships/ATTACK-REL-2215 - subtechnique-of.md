---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1496.001"
target_object: "T1496"
stix_relationship_id: "relationship--10b76c75-11f1-421d-899a-30d22f7e8260"
---
# Relationship 2215: T1496.001 — subtechnique-of → T1496

**Source object:** [[01 ATT&CK/T1496.001 - Compute Hijacking|T1496.001: Compute Hijacking]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1496 - Resource Hijacking|T1496: Resource Hijacking]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--10b76c75-11f1-421d-899a-30d22f7e8260`.
