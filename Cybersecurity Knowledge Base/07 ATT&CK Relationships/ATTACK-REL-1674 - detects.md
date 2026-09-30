---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0215"
target_object: "T1486"
stix_relationship_id: "relationship--245046a7-adc8-4a5a-84b4-e0af6c3b8dc7"
---
# Relationship 1674: DET0215 — detects → T1486

**Source object:** [[01 ATT&CK/DET0215 - Detection of Multi-Platform File Encryption for Impact|DET0215: Detection of Multi-Platform File Encryption for Impact]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1486 - Data Encrypted for Impact|T1486: Data Encrypted for Impact]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--245046a7-adc8-4a5a-84b4-e0af6c3b8dc7`.
