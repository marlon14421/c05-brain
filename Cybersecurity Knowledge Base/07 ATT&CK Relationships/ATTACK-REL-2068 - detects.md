---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0165"
target_object: "T1070.003"
stix_relationship_id: "relationship--eddaad17-65b1-4c89-a274-1a797080933e"
---
# Relationship 2068: DET0165 — detects → T1070.003

**Source object:** [[01 ATT&CK/DET0165 - Behavioral Detection of Command History Clearing|DET0165: Behavioral Detection of Command History Clearing]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1070.003 - Clear Command History|T1070.003: Clear Command History]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--eddaad17-65b1-4c89-a274-1a797080933e`.
