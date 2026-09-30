---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0520"
target_object: "T1685.006"
stix_relationship_id: "relationship--b1572a43-bc01-496f-a92b-3363941af84a"
---
# Relationship 1858: DET0520 — detects → T1685.006

**Source object:** [[01 ATT&CK/DET0520 - Behavioral Detection of Log File Clearing on Linux and macOS|DET0520: Behavioral Detection of Log File Clearing on Linux and macOS]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1685.006 - Clear Linux or Mac System Logs|T1685.006: Clear Linux or Mac System Logs]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b1572a43-bc01-496f-a92b-3363941af84a`.
