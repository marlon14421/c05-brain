---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0841"
target_object: "T1589"
stix_relationship_id: "relationship--601e71a6-90b3-4a69-8457-543659474d26"
---
# Relationship 1608: DET0841 — detects → T1589

**Source object:** [[01 ATT&CK/DET0841 - Detection of Gather Victim Identity Information|DET0841: Detection of Gather Victim Identity Information]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1589 - Gather Victim Identity Information|T1589: Gather Victim Identity Information]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--601e71a6-90b3-4a69-8457-543659474d26`.
