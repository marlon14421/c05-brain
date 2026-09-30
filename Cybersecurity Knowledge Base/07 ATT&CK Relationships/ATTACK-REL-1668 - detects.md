---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0172"
target_object: "T1127"
stix_relationship_id: "relationship--e9ff67a4-4136-46d0-b91e-d354c84215a1"
---
# Relationship 1668: DET0172 — detects → T1127

**Source object:** [[01 ATT&CK/DET0172 - Behavior-chain, platform-aware detection strategy for T1127 Trusted Developer Utiliti|DET0172: Behavior-chain, platform-aware detection strategy for T1127 Trusted Developer Utilities Proxy Execution (Windows)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1127 - Trusted Developer Utilities Proxy Execution|T1127: Trusted Developer Utilities Proxy Execution]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e9ff67a4-4136-46d0-b91e-d354c84215a1`.
