---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0082"
target_object: "T1491.001"
stix_relationship_id: "relationship--0222a8bd-9f8c-45f0-9d1b-cb0a2bd3c408"
---
# Relationship 1620: DET0082 — detects → T1491.001

**Source object:** [[01 ATT&CK/DET0082 - Internal Website and System Content Defacement via UI or Messaging Modifications|DET0082: Internal Website and System Content Defacement via UI or Messaging Modifications]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1491.001 - Internal Defacement|T1491.001: Internal Defacement]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0222a8bd-9f8c-45f0-9d1b-cb0a2bd3c408`.
