---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0828"
target_object: "T1590.003"
stix_relationship_id: "relationship--ee548a90-95df-4f9d-87c3-68aee0ce9b9d"
---
# Relationship 1721: DET0828 — detects → T1590.003

**Source object:** [[01 ATT&CK/DET0828 - Detection of Network Trust Dependencies|DET0828: Detection of Network Trust Dependencies]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1590.003 - Network Trust Dependencies|T1590.003: Network Trust Dependencies]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ee548a90-95df-4f9d-87c3-68aee0ce9b9d`.
