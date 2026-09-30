---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0839"
target_object: "T1608"
stix_relationship_id: "relationship--d5cb2afa-69f8-4705-9a19-5b1add24494a"
---
# Relationship 1986: DET0839 — detects → T1608

**Source object:** [[01 ATT&CK/DET0839 - Detection of Stage Capabilities|DET0839: Detection of Stage Capabilities]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1608 - Stage Capabilities|T1608: Stage Capabilities]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d5cb2afa-69f8-4705-9a19-5b1add24494a`.
