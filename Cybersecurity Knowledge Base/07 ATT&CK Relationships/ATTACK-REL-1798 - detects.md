---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0840"
target_object: "T1608.003"
stix_relationship_id: "relationship--2ca3b573-eacb-43c9-b054-7582e6c20828"
---
# Relationship 1798: DET0840 — detects → T1608.003

**Source object:** [[01 ATT&CK/DET0840 - Detection of Install Digital Certificate|DET0840: Detection of Install Digital Certificate]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1608.003 - Install Digital Certificate|T1608.003: Install Digital Certificate]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2ca3b573-eacb-43c9-b054-7582e6c20828`.
