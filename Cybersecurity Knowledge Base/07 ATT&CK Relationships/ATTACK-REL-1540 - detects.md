---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0820"
target_object: "T1592.004"
stix_relationship_id: "relationship--e346361d-dc1a-49f6-bebe-c475ab8b3af3"
---
# Relationship 1540: DET0820 — detects → T1592.004

**Source object:** [[01 ATT&CK/DET0820 - Detection of Client Configurations|DET0820: Detection of Client Configurations]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1592.004 - Client Configurations|T1592.004: Client Configurations]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e346361d-dc1a-49f6-bebe-c475ab8b3af3`.
