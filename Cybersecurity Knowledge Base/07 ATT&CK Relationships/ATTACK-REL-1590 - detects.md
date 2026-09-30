---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0458"
target_object: "T1484.002"
stix_relationship_id: "relationship--9bf2d865-47fe-447d-b49f-1cfbcb92feca"
---
# Relationship 1590: DET0458 — detects → T1484.002

**Source object:** [[01 ATT&CK/DET0458 - Detection of Trust Relationship Modifications in Domain or Tenant Policies|DET0458: Detection of Trust Relationship Modifications in Domain or Tenant Policies]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1484.002 - Trust Modification|T1484.002: Trust Modification]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9bf2d865-47fe-447d-b49f-1cfbcb92feca`.
