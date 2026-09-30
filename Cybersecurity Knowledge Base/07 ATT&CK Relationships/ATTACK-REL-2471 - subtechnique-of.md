---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1548.001"
target_object: "T1548"
stix_relationship_id: "relationship--2d7deb28-0fcf-495b-9d41-01529d356674"
---
# Relationship 2471: T1548.001 — subtechnique-of → T1548

**Source object:** [[01 ATT&CK/T1548.001 - Setuid and Setgid|T1548.001: Setuid and Setgid]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1548 - Abuse Elevation Control Mechanism|T1548: Abuse Elevation Control Mechanism]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2d7deb28-0fcf-495b-9d41-01529d356674`.
