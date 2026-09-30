---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0585"
target_object: "T1127.003"
stix_relationship_id: "relationship--cf8ed394-7e83-4637-9cd3-82cccd529d78"
---
# Relationship 2101: DET0585 — detects → T1127.003

**Source object:** [[01 ATT&CK/DET0585 - Behavior-chain detection strategy for T1127.003 Trusted Developer Utilities Proxy Exe|DET0585: Behavior-chain detection strategy for T1127.003 Trusted Developer Utilities Proxy Execution: JamPlus (Windows)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1127.003 - JamPlus|T1127.003: JamPlus]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cf8ed394-7e83-4637-9cd3-82cccd529d78`.
