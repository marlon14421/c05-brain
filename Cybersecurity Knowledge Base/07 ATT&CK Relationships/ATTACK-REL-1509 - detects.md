---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0245"
target_object: "T1566.004"
stix_relationship_id: "relationship--2b2f1df3-9863-440c-9451-d9cfa1581609"
---
# Relationship 1509: DET0245 — detects → T1566.004

**Source object:** [[01 ATT&CK/DET0245 - Detection Strategy for Spearphishing Voice across OS platforms|DET0245: Detection Strategy for Spearphishing Voice across OS platforms]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1566.004 - Spearphishing Voice|T1566.004: Spearphishing Voice]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2b2f1df3-9863-440c-9451-d9cfa1581609`.
