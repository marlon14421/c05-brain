---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0857"
target_object: "T1589.003"
stix_relationship_id: "relationship--bad95134-a647-46a8-a403-a74f0250e4e8"
---
# Relationship 1985: DET0857 — detects → T1589.003

**Source object:** [[01 ATT&CK/DET0857 - Detection of Employee Names|DET0857: Detection of Employee Names]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1589.003 - Employee Names|T1589.003: Employee Names]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bad95134-a647-46a8-a403-a74f0250e4e8`.
