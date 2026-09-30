---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0354"
target_object: "T1133"
stix_relationship_id: "relationship--0b58aa79-627a-4d83-84ab-fb924e5f77e1"
---
# Relationship 1933: DET0354 — detects → T1133

**Source object:** [[01 ATT&CK/DET0354 - Behavior-chain detection for T1133 External Remote Services across Windows, Linux, ma|DET0354: Behavior-chain detection for T1133 External Remote Services across Windows, Linux, macOS, Containers]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1133 - External Remote Services|T1133: External Remote Services]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0b58aa79-627a-4d83-84ab-fb924e5f77e1`.
