---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0234"
target_object: "T1003"
stix_relationship_id: "relationship--a9f91861-99e7-4dee-b037-9c6fd56e9892"
---
# Relationship 1875: DET0234 — detects → T1003

**Source object:** [[01 ATT&CK/DET0234 - Credential Dumping via Sensitive Memory and Registry Access Correlation|DET0234: Credential Dumping via Sensitive Memory and Registry Access Correlation]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1003 - OS Credential Dumping|T1003: OS Credential Dumping]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a9f91861-99e7-4dee-b037-9c6fd56e9892`.
