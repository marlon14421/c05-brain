---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0521"
target_object: "T1056.002"
stix_relationship_id: "relationship--a6a8076f-c1d4-4b6c-845e-82022cff159c"
---
# Relationship 1820: DET0521 — detects → T1056.002

**Source object:** [[01 ATT&CK/DET0521 - Behavioral Detection of Spoofed GUI Credential Prompts|DET0521: Behavioral Detection of Spoofed GUI Credential Prompts]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1056.002 - GUI Input Capture|T1056.002: GUI Input Capture]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a6a8076f-c1d4-4b6c-845e-82022cff159c`.
