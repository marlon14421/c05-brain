---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1590.004"
target_object: "T1590"
stix_relationship_id: "relationship--8ab253ed-9bf8-4e0d-b367-f9d5349a7cfc"
---
# Relationship 2402: T1590.004 — subtechnique-of → T1590

**Source object:** [[01 ATT&CK/T1590.004 - Network Topology|T1590.004: Network Topology]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1590 - Gather Victim Network Information|T1590: Gather Victim Network Information]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8ab253ed-9bf8-4e0d-b367-f9d5349a7cfc`.
