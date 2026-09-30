---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0256"
target_object: "T1563.001"
stix_relationship_id: "relationship--d9456903-054e-4281-b9f3-b95c5bf42f6e"
---
# Relationship 1778: DET0256 — detects → T1563.001

**Source object:** [[01 ATT&CK/DET0256 - Detection Strategy for SSH Session Hijacking|DET0256: Detection Strategy for SSH Session Hijacking]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1563.001 - SSH Hijacking|T1563.001: SSH Hijacking]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d9456903-054e-4281-b9f3-b95c5bf42f6e`.
