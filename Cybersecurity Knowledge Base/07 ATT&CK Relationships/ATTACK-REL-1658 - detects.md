---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0487"
target_object: "T1110.003"
stix_relationship_id: "relationship--aff15269-2b23-4e7e-8fc7-8ab27dace6cc"
---
# Relationship 1658: DET0487 — detects → T1110.003

**Source object:** [[01 ATT&CK/DET0487 - Distributed Password Spraying via Authentication Failures Across Multiple Accounts|DET0487: Distributed Password Spraying via Authentication Failures Across Multiple Accounts]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1110.003 - Password Spraying|T1110.003: Password Spraying]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--aff15269-2b23-4e7e-8fc7-8ab27dace6cc`.
