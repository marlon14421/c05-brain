---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1021.006"
target_object: "T1021"
stix_relationship_id: "relationship--22e8b7b4-7e5f-45a8-a935-c4cc7da638f2"
---
# Relationship 2395: T1021.006 — subtechnique-of → T1021

**Source object:** [[01 ATT&CK/T1021.006 - Windows Remote Management|T1021.006: Windows Remote Management]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1021 - Remote Services|T1021: Remote Services]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--22e8b7b4-7e5f-45a8-a935-c4cc7da638f2`.
