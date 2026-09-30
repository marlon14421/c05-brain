---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0335"
target_object: "T1559.003"
stix_relationship_id: "relationship--7cc39b6e-1b98-41d6-b57f-12f6b66f93a0"
---
# Relationship 1782: DET0335 — detects → T1559.003

**Source object:** [[01 ATT&CK/DET0335 - Detect Abuse of XPC Services (T1559.003)|DET0335: Detect Abuse of XPC Services (T1559.003)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1559.003 - XPC Services|T1559.003: XPC Services]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7cc39b6e-1b98-41d6-b57f-12f6b66f93a0`.
