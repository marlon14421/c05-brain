---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0563"
target_object: "T1690"
stix_relationship_id: "relationship--e3fdb794-f7c3-4add-858b-bb8f3f79175d"
---
# Relationship 1703: DET0563 — detects → T1690

**Source object:** [[01 ATT&CK/DET0563 - Detection Strategy for Defense Impairment via Prevent Command History Logging across |DET0563: Detection Strategy for Defense Impairment via Prevent Command History Logging across OS platforms.]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1690 - Prevent Command History Logging|T1690: Prevent Command History Logging]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e3fdb794-f7c3-4add-858b-bb8f3f79175d`.
