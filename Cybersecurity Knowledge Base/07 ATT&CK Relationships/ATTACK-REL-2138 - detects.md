---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0191"
target_object: "T1127.002"
stix_relationship_id: "relationship--a06bc62f-b3e7-468b-8697-1e00367bc28b"
---
# Relationship 2138: DET0191 — detects → T1127.002

**Source object:** [[01 ATT&CK/DET0191 - Behavior-chain detection strategy for T1127.002 Trusted Developer Utilities Proxy Exe|DET0191: Behavior-chain detection strategy for T1127.002 Trusted Developer Utilities Proxy Execution: ClickOnce (Windows)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1127.002 - ClickOnce|T1127.002: ClickOnce]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a06bc62f-b3e7-468b-8697-1e00367bc28b`.
