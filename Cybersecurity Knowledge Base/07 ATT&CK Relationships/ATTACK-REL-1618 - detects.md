---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0309"
target_object: "T1195.002"
stix_relationship_id: "relationship--91cd8b1f-5c87-41be-b7e7-310d4c6b6c3e"
---
# Relationship 1618: DET0309 — detects → T1195.002

**Source object:** [[01 ATT&CK/DET0309 - Compromised software-update chain (installer-write → first-run-child → egress-signatu|DET0309: Compromised software/update chain (installer/write → first-run/child → egress/signature anomaly)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1195.002 - Compromise Software Supply Chain|T1195.002: Compromise Software Supply Chain]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--91cd8b1f-5c87-41be-b7e7-310d4c6b6c3e`.
