---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0231"
target_object: "T1053.006"
stix_relationship_id: "relationship--5d260af9-40a1-45ba-b98f-83abe6d89e42"
---
# Relationship 1553: DET0231 — detects → T1053.006

**Source object:** [[01 ATT&CK/DET0231 - Behavioral Detection of Systemd Timer Abuse for Scheduled Execution|DET0231: Behavioral Detection of Systemd Timer Abuse for Scheduled Execution]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1053.006 - Systemd Timers|T1053.006: Systemd Timers]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5d260af9-40a1-45ba-b98f-83abe6d89e42`.
