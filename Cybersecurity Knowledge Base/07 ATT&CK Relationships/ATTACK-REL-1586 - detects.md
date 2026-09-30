---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0508"
target_object: "T1055"
stix_relationship_id: "relationship--9e795af2-1202-480c-88d1-5013027ede32"
---
# Relationship 1586: DET0508 — detects → T1055

**Source object:** [[01 ATT&CK/DET0508 - Behavioral Detection of Process Injection Across Platforms|DET0508: Behavioral Detection of Process Injection Across Platforms]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1055 - Process Injection|T1055: Process Injection]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9e795af2-1202-480c-88d1-5013027ede32`.
