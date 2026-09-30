---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0890"
target_object: "T1591"
stix_relationship_id: "relationship--b35d6a1a-324d-4495-87b2-216b57b2afb1"
---
# Relationship 1864: DET0890 — detects → T1591

**Source object:** [[01 ATT&CK/DET0890 - Detection of Gather Victim Org Information|DET0890: Detection of Gather Victim Org Information]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1591 - Gather Victim Org Information|T1591: Gather Victim Org Information]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b35d6a1a-324d-4495-87b2-216b57b2afb1`.
