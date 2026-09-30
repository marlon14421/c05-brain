---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0288"
target_object: "T1553.001"
stix_relationship_id: "relationship--28c76ea2-9274-4291-b452-6c25bedbb4e4"
---
# Relationship 1637: DET0288 — detects → T1553.001

**Source object:** [[01 ATT&CK/DET0288 - Detect Gatekeeper Bypass via Quarantine Flag and Trust Control Manipulation|DET0288: Detect Gatekeeper Bypass via Quarantine Flag and Trust Control Manipulation]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1553.001 - Gatekeeper Bypass|T1553.001: Gatekeeper Bypass]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--28c76ea2-9274-4291-b452-6c25bedbb4e4`.
