---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0249"
target_object: "T1610"
stix_relationship_id: "relationship--51ae0fd9-6c66-4f7f-94ec-734259ba9140"
---
# Relationship 1926: DET0249 — detects → T1610

**Source object:** [[01 ATT&CK/DET0249 - Behavior-chain detection for T1610 Deploy Container across Docker & Kubernetes contro|DET0249: Behavior-chain detection for T1610 Deploy Container across Docker & Kubernetes control/node planes]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1610 - Deploy Container|T1610: Deploy Container]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--51ae0fd9-6c66-4f7f-94ec-734259ba9140`.
