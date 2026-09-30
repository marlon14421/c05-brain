---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0856"
target_object: "T1593"
stix_relationship_id: "relationship--07c64cca-093f-4ba5-afb3-5214c5a645d4"
---
# Relationship 1724: DET0856 — detects → T1593

**Source object:** [[01 ATT&CK/DET0856 - Detection of Search Open Websites-Domains|DET0856: Detection of Search Open Websites/Domains]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1593 - Search Open Websites-Domains|T1593: Search Open Websites/Domains]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--07c64cca-093f-4ba5-afb3-5214c5a645d4`.
