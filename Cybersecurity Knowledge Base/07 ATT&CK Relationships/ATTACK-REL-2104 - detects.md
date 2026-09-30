---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0846"
target_object: "T1585.003"
stix_relationship_id: "relationship--63a37b98-049b-4561-a4c8-adaef8b7613a"
---
# Relationship 2104: DET0846 — detects → T1585.003

**Source object:** [[01 ATT&CK/DET0846 - Detection of Cloud Accounts|DET0846: Detection of Cloud Accounts]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1585.003 - Cloud Accounts|T1585.003: Cloud Accounts]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--63a37b98-049b-4561-a4c8-adaef8b7613a`.
