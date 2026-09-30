---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0113"
target_object: "T1558.004"
stix_relationship_id: "relationship--7be88280-2aa7-4661-9ee1-b9f74e58a49c"
---
# Relationship 1867: DET0113 — detects → T1558.004

**Source object:** [[01 ATT&CK/DET0113 - Detect AS-REP Roasting Attempts (T1558.004)|DET0113: Detect AS-REP Roasting Attempts (T1558.004)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1558.004 - AS-REP Roasting|T1558.004: AS-REP Roasting]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7be88280-2aa7-4661-9ee1-b9f74e58a49c`.
