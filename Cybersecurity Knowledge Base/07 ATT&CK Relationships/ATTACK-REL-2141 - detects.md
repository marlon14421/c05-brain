---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0552"
target_object: "T1543.003"
stix_relationship_id: "relationship--67c2ad46-15c3-45d1-b209-4921f21eb8c3"
---
# Relationship 2141: DET0552 — detects → T1543.003

**Source object:** [[01 ATT&CK/DET0552 - Detection of Windows Service Creation or Modification|DET0552: Detection of Windows Service Creation or Modification]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1543.003 - Windows Service|T1543.003: Windows Service]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--67c2ad46-15c3-45d1-b209-4921f21eb8c3`.
