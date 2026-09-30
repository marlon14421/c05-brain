---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0009"
target_object: "T1195.001"
stix_relationship_id: "relationship--f21676c2-dc39-4d2e-b551-5ed654dddef3"
---
# Relationship 2130: DET0009 — detects → T1195.001

**Source object:** [[01 ATT&CK/DET0009 - Supply-chain tamper in dependencies-dev-tools (manager→write-install→first-run→egress|DET0009: Supply-chain tamper in dependencies/dev-tools (manager→write/install→first-run→egress)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1195.001 - Compromise Software Dependencies and Development Tools|T1195.001: Compromise Software Dependencies and Development Tools]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f21676c2-dc39-4d2e-b551-5ed654dddef3`.
