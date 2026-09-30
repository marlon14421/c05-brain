---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0341"
target_object: "T1115"
stix_relationship_id: "relationship--120b3e62-84c4-4bf4-884a-97393654e17b"
---
# Relationship 1911: DET0341 — detects → T1115

**Source object:** [[01 ATT&CK/DET0341 - Clipboard Data Access with Anomalous Context|DET0341: Clipboard Data Access with Anomalous Context]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1115 - Clipboard Data|T1115: Clipboard Data]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--120b3e62-84c4-4bf4-884a-97393654e17b`.
