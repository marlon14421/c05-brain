---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0480"
target_object: "T1056.003"
stix_relationship_id: "relationship--a7ed21d5-98f1-4851-a163-f770a64fc7aa"
---
# Relationship 2140: DET0480 — detects → T1056.003

**Source object:** [[01 ATT&CK/DET0480 - Detection of Credential Harvesting via Web Portal Modification|DET0480: Detection of Credential Harvesting via Web Portal Modification]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1056.003 - Web Portal Capture|T1056.003: Web Portal Capture]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a7ed21d5-98f1-4851-a163-f770a64fc7aa`.
