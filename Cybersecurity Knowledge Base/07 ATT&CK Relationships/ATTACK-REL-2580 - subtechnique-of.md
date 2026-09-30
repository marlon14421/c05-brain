---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1595.001"
target_object: "T1595"
stix_relationship_id: "relationship--9feede0a-38c3-4aa7-8416-c2b0d0d67f83"
---
# Relationship 2580: T1595.001 — subtechnique-of → T1595

**Source object:** [[01 ATT&CK/T1595.001 - Scanning IP Blocks|T1595.001: Scanning IP Blocks]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1595 - Active Scanning|T1595: Active Scanning]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9feede0a-38c3-4aa7-8416-c2b0d0d67f83`.
