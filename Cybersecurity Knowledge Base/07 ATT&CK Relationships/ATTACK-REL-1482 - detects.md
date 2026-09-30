---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0465"
target_object: "T1078.001"
stix_relationship_id: "relationship--373bb9b1-c8ef-4614-b1a4-9e3eefa27a1a"
---
# Relationship 1482: DET0465 — detects → T1078.001

**Source object:** [[01 ATT&CK/DET0465 - Detection of Default Account Abuse Across Platforms|DET0465: Detection of Default Account Abuse Across Platforms]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1078.001 - Default Accounts|T1078.001: Default Accounts]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--373bb9b1-c8ef-4614-b1a4-9e3eefa27a1a`.
