---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1070.004"
target_object: "T1070"
stix_relationship_id: "relationship--05e3980c-03ae-4624-82d8-0cbcc45705cd"
---
# Relationship 2475: T1070.004 — subtechnique-of → T1070

**Source object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1070 - Indicator Removal|T1070: Indicator Removal]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--05e3980c-03ae-4624-82d8-0cbcc45705cd`.
