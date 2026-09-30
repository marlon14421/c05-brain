---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0463"
target_object: "T1110"
stix_relationship_id: "relationship--5cf10b86-166a-4ff1-8b30-715bf232b540"
---
# Relationship 1883: DET0463 — detects → T1110

**Source object:** [[01 ATT&CK/DET0463 - Brute Force Authentication Failures with Multi-Platform Log Correlation|DET0463: Brute Force Authentication Failures with Multi-Platform Log Correlation]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1110 - Brute Force|T1110: Brute Force]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5cf10b86-166a-4ff1-8b30-715bf232b540`.
