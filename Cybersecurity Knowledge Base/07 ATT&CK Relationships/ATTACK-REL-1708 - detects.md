---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0085"
target_object: "T1003.002"
stix_relationship_id: "relationship--310c8128-3ebf-48fd-b207-d81e5251a686"
---
# Relationship 1708: DET0085 — detects → T1003.002

**Source object:** [[01 ATT&CK/DET0085 - Credential Dumping from SAM via Registry Dump and Local File Access|DET0085: Credential Dumping from SAM via Registry Dump and Local File Access]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1003.002 - Security Account Manager|T1003.002: Security Account Manager]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--310c8128-3ebf-48fd-b207-d81e5251a686`.
