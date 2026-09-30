---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1587.003"
target_object: "T1587"
stix_relationship_id: "relationship--b316741b-8bd3-4af6-9d5c-76afca7b9012"
---
# Relationship 2459: T1587.003 — subtechnique-of → T1587

**Source object:** [[01 ATT&CK/T1587.003 - Digital Certificates|T1587.003: Digital Certificates]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1587 - Develop Capabilities|T1587: Develop Capabilities]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b316741b-8bd3-4af6-9d5c-76afca7b9012`.
