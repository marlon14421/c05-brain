---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0413"
target_object: "T1213"
stix_relationship_id: "relationship--9f605e91-c94f-48b0-ab9f-1d692649eca5"
---
# Relationship 1823: DET0413 — detects → T1213

**Source object:** [[01 ATT&CK/DET0413 - Abuse of Information Repositories for Data Collection|DET0413: Abuse of Information Repositories for Data Collection]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1213 - Data from Information Repositories|T1213: Data from Information Repositories]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9f605e91-c94f-48b0-ab9f-1d692649eca5`.
