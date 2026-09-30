---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0891"
target_object: "T1584.002"
stix_relationship_id: "relationship--f8f6b5ea-1c74-482e-965c-e6bc676d04b2"
---
# Relationship 1673: DET0891 — detects → T1584.002

**Source object:** [[01 ATT&CK/DET0891 - Detection of DNS Server|DET0891: Detection of DNS Server]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1584.002 - DNS Server|T1584.002: DNS Server]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f8f6b5ea-1c74-482e-965c-e6bc676d04b2`.
