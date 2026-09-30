---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0021"
target_object: "T1489"
stix_relationship_id: "relationship--091187a1-a960-4731-829d-de865e7d49a1"
---
# Relationship 1477: DET0021 — detects → T1489

**Source object:** [[01 ATT&CK/DET0021 - Behavioral Detection for Service Stop across Platforms|DET0021: Behavioral Detection for Service Stop across Platforms]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1489 - Service Stop|T1489: Service Stop]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--091187a1-a960-4731-829d-de865e7d49a1`.
