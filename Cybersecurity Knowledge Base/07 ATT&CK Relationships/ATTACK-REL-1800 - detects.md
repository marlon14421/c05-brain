---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0576"
target_object: "T1114.003"
stix_relationship_id: "relationship--097ad539-3af8-45a7-9804-7f8925c693a3"
---
# Relationship 1800: DET0576 — detects → T1114.003

**Source object:** [[01 ATT&CK/DET0576 - Email Forwarding Rule Abuse Detection Across Platforms|DET0576: Email Forwarding Rule Abuse Detection Across Platforms]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1114.003 - Email Forwarding Rule|T1114.003: Email Forwarding Rule]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--097ad539-3af8-45a7-9804-7f8925c693a3`.
