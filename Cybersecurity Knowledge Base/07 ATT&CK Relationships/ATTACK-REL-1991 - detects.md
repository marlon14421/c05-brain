---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0096"
target_object: "T1098"
stix_relationship_id: "relationship--94a27c31-1cda-4987-b42b-ed1868631177"
---
# Relationship 1991: DET0096 — detects → T1098

**Source object:** [[01 ATT&CK/DET0096 - Account Manipulation Behavior Chain Detection|DET0096: Account Manipulation Behavior Chain Detection]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1098 - Account Manipulation|T1098: Account Manipulation]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--94a27c31-1cda-4987-b42b-ed1868631177`.
