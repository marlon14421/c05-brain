---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1056.002"
target_object: "T1056"
stix_relationship_id: "relationship--6db133fd-2beb-4c5e-a97c-3d3ef03bee50"
---
# Relationship 2189: T1056.002 — subtechnique-of → T1056

**Source object:** [[01 ATT&CK/T1056.002 - GUI Input Capture|T1056.002: GUI Input Capture]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1056 - Input Capture|T1056: Input Capture]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6db133fd-2beb-4c5e-a97c-3d3ef03bee50`.
