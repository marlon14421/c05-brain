---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0263"
target_object: "T1213.003"
stix_relationship_id: "relationship--8b6e293f-6992-4fca-bb50-ddb4ae7c406c"
---
# Relationship 2081: DET0263 — detects → T1213.003

**Source object:** [[01 ATT&CK/DET0263 - Detecting Bulk or Anomalous Access to Private Code Repositories via SaaS Platforms|DET0263: Detecting Bulk or Anomalous Access to Private Code Repositories via SaaS Platforms]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1213.003 - Code Repositories|T1213.003: Code Repositories]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8b6e293f-6992-4fca-bb50-ddb4ae7c406c`.
