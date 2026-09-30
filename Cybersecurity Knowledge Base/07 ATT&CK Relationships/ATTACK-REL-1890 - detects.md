---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0399"
target_object: "T1029"
stix_relationship_id: "relationship--7e72a636-f8c4-449d-b508-db4910fc497c"
---
# Relationship 1890: DET0399 — detects → T1029

**Source object:** [[01 ATT&CK/DET0399 - Detection Strategy for Scheduled Transfer and Recurrent Exfiltration Patterns|DET0399: Detection Strategy for Scheduled Transfer and Recurrent Exfiltration Patterns]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1029 - Scheduled Transfer|T1029: Scheduled Transfer]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7e72a636-f8c4-449d-b508-db4910fc497c`.
