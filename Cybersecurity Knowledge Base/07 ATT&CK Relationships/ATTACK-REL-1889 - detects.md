---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0160"
target_object: "T1621"
stix_relationship_id: "relationship--3061a5d3-7c23-41ff-bc7e-7cd916b4bfc7"
---
# Relationship 1889: DET0160 — detects → T1621

**Source object:** [[01 ATT&CK/DET0160 - Detection Strategy for Multi-Factor Authentication Request Generation (T1621)|DET0160: Detection Strategy for Multi-Factor Authentication Request Generation (T1621)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1621 - Multi-Factor Authentication Request Generation|T1621: Multi-Factor Authentication Request Generation]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3061a5d3-7c23-41ff-bc7e-7cd916b4bfc7`.
