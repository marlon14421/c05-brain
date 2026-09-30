---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0025"
target_object: "T1218.015"
stix_relationship_id: "relationship--2d9779a5-5d91-40ba-8475-4264b261a8f8"
---
# Relationship 2009: DET0025 — detects → T1218.015

**Source object:** [[01 ATT&CK/DET0025 - Detecting Electron Application Abuse for Proxy Execution|DET0025: Detecting Electron Application Abuse for Proxy Execution]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1218.015 - Electron Applications|T1218.015: Electron Applications]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2d9779a5-5d91-40ba-8475-4264b261a8f8`.
