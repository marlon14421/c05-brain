---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0885"
target_object: "T1584"
stix_relationship_id: "relationship--8d89d562-7ca0-4ba7-9ccc-dddbb7de1866"
---
# Relationship 1992: DET0885 — detects → T1584

**Source object:** [[01 ATT&CK/DET0885 - Detection of Compromise Infrastructure|DET0885: Detection of Compromise Infrastructure]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1584 - Compromise Infrastructure|T1584: Compromise Infrastructure]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8d89d562-7ca0-4ba7-9ccc-dddbb7de1866`.
