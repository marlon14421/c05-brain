---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0126"
target_object: "T1098.004"
stix_relationship_id: "relationship--ace534ca-793e-4d09-8ed1-5d941ac89285"
---
# Relationship 1542: DET0126 — detects → T1098.004

**Source object:** [[01 ATT&CK/DET0126 - Detection Strategy for SSH Key Injection in Authorized Keys|DET0126: Detection Strategy for SSH Key Injection in Authorized Keys]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1098.004 - SSH Authorized Keys|T1098.004: SSH Authorized Keys]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ace534ca-793e-4d09-8ed1-5d941ac89285`.
