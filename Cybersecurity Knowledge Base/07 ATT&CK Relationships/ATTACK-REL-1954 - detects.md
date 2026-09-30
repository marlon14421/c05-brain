---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0325"
target_object: "T1090.002"
stix_relationship_id: "relationship--872ebb9f-131c-47e0-a8c3-15b4764d3594"
---
# Relationship 1954: DET0325 — detects → T1090.002

**Source object:** [[01 ATT&CK/DET0325 - External Proxy Behavior via Outbound Relay to Intermediate Infrastructure|DET0325: External Proxy Behavior via Outbound Relay to Intermediate Infrastructure]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1090.002 - External Proxy|T1090.002: External Proxy]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--872ebb9f-131c-47e0-a8c3-15b4764d3594`.
