---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0813"
target_object: "T1589.001"
stix_relationship_id: "relationship--925f9ad8-851b-4fff-87a2-ae14b1b5d4c2"
---
# Relationship 1918: DET0813 — detects → T1589.001

**Source object:** [[01 ATT&CK/DET0813 - Detection of Credentials|DET0813: Detection of Credentials]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1589.001 - Credentials|T1589.001: Credentials]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--925f9ad8-851b-4fff-87a2-ae14b1b5d4c2`.
