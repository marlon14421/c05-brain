---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0420"
target_object: "T1497.002"
stix_relationship_id: "relationship--0e9828c1-9cf3-44a2-b079-41bb6fa79656"
---
# Relationship 1758: DET0420 — detects → T1497.002

**Source object:** [[01 ATT&CK/DET0420 - Detect User Activity Based Sandbox Evasion via Input & Artifact Probing|DET0420: Detect User Activity Based Sandbox Evasion via Input & Artifact Probing]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1497.002 - User Activity Based Checks|T1497.002: User Activity Based Checks]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0e9828c1-9cf3-44a2-b079-41bb6fa79656`.
