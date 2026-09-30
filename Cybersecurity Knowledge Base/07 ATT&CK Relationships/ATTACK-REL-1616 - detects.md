---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0356"
target_object: "T1499.001"
stix_relationship_id: "relationship--2027adf0-d101-4183-865b-f377ea9df209"
---
# Relationship 1616: DET0356 — detects → T1499.001

**Source object:** [[01 ATT&CK/DET0356 - Endpoint DoS via OS Exhaustion Flood Detection Strategy|DET0356: Endpoint DoS via OS Exhaustion Flood Detection Strategy]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1499.001 - OS Exhaustion Flood|T1499.001: OS Exhaustion Flood]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2027adf0-d101-4183-865b-f377ea9df209`.
