---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0053"
target_object: "T1001"
stix_relationship_id: "relationship--7ed4c50d-fb81-4d1b-b89f-6a8d81994887"
---
# Relationship 1526: DET0053 — detects → T1001

**Source object:** [[01 ATT&CK/DET0053 - Detect Obfuscated C2 via Network Traffic Analysis|DET0053: Detect Obfuscated C2 via Network Traffic Analysis]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1001 - Data Obfuscation|T1001: Data Obfuscation]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7ed4c50d-fb81-4d1b-b89f-6a8d81994887`.
