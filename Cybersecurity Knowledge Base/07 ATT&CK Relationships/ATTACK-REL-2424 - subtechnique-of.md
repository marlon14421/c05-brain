---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1598.001"
target_object: "T1598"
stix_relationship_id: "relationship--a299b456-78d0-4cf2-accc-4dfd7b5cd74d"
---
# Relationship 2424: T1598.001 — subtechnique-of → T1598

**Source object:** [[01 ATT&CK/T1598.001 - Spearphishing Service|T1598.001: Spearphishing Service]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1598 - Phishing for Information|T1598: Phishing for Information]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a299b456-78d0-4cf2-accc-4dfd7b5cd74d`.
