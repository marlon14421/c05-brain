---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0238"
target_object: "T1491"
stix_relationship_id: "relationship--84ae8dca-13f2-420f-b473-0d28480e2002"
---
# Relationship 2025: DET0238 — detects → T1491

**Source object:** [[01 ATT&CK/DET0238 - Defacement via File and Web Content Modification Across Platforms|DET0238: Defacement via File and Web Content Modification Across Platforms]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1491 - Defacement|T1491: Defacement]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--84ae8dca-13f2-420f-b473-0d28480e2002`.
