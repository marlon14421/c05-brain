---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0504"
target_object: "T1559.002"
stix_relationship_id: "relationship--1e59c2f0-d933-478b-ba5c-f1518a467465"
---
# Relationship 1900: DET0504 — detects → T1559.002

**Source object:** [[01 ATT&CK/DET0504 - Detect Abuse of Dynamic Data Exchange (T1559.002)|DET0504: Detect Abuse of Dynamic Data Exchange (T1559.002)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1559.002 - Dynamic Data Exchange|T1559.002: Dynamic Data Exchange]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1e59c2f0-d933-478b-ba5c-f1518a467465`.
