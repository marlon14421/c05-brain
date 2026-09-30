---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0407"
target_object: "T1078.003"
stix_relationship_id: "relationship--2f51d6e5-68fe-426c-931c-e33b5bdc3289"
---
# Relationship 1550: DET0407 — detects → T1078.003

**Source object:** [[01 ATT&CK/DET0407 - Detection of Local Account Abuse for Initial Access and Persistence|DET0407: Detection of Local Account Abuse for Initial Access and Persistence]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1078.003 - Local Accounts|T1078.003: Local Accounts]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2f51d6e5-68fe-426c-931c-e33b5bdc3289`.
