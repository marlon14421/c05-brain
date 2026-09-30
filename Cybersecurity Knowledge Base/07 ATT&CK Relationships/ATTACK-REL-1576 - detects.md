---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0013"
target_object: "T1217"
stix_relationship_id: "relationship--48832f2d-d088-4d32-b41d-b15030559f96"
---
# Relationship 1576: DET0013 — detects → T1217

**Source object:** [[01 ATT&CK/DET0013 - Detection of Local Browser Artifact Access for Reconnaissance|DET0013: Detection of Local Browser Artifact Access for Reconnaissance]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1217 - Browser Information Discovery|T1217: Browser Information Discovery]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--48832f2d-d088-4d32-b41d-b15030559f96`.
