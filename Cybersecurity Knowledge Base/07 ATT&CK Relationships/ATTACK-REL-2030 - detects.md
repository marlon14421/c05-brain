---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0532"
target_object: "T1685.005"
stix_relationship_id: "relationship--d2eddf20-7246-454b-8da6-412dce453128"
---
# Relationship 2030: DET0532 — detects → T1685.005

**Source object:** [[01 ATT&CK/DET0532 - Detection of Event Log Clearing on Windows via Behavioral Chain|DET0532: Detection of Event Log Clearing on Windows via Behavioral Chain]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1685.005 - Clear Windows Event Logs|T1685.005: Clear Windows Event Logs]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d2eddf20-7246-454b-8da6-412dce453128`.
