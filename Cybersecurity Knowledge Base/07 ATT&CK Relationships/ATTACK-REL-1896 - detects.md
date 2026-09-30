---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0018"
target_object: "T1129"
stix_relationship_id: "relationship--20d31ad8-56fd-4268-b650-6106617cc9bc"
---
# Relationship 1896: DET0018 — detects → T1129

**Source object:** [[01 ATT&CK/DET0018 - Behavior-chain, platform-aware detection strategy for T1129 Shared Modules|DET0018: Behavior-chain, platform-aware detection strategy for T1129 Shared Modules]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1129 - Shared Modules|T1129: Shared Modules]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--20d31ad8-56fd-4268-b650-6106617cc9bc`.
