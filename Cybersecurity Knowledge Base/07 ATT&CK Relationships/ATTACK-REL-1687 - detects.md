---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0869"
target_object: "T1590"
stix_relationship_id: "relationship--c328babb-055f-447f-b5be-cdf1b67bdfbf"
---
# Relationship 1687: DET0869 — detects → T1590

**Source object:** [[01 ATT&CK/DET0869 - Detection of Gather Victim Network Information|DET0869: Detection of Gather Victim Network Information]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1590 - Gather Victim Network Information|T1590: Gather Victim Network Information]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c328babb-055f-447f-b5be-cdf1b67bdfbf`.
