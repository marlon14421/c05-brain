---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0027"
target_object: "T1071.001"
stix_relationship_id: "relationship--c392a03d-b4d0-4b2c-aeaa-1b010d916922"
---
# Relationship 1731: DET0027 — detects → T1071.001

**Source object:** [[01 ATT&CK/DET0027 - Detection of Web Protocol-Based C2 Over HTTP, HTTPS, or WebSockets|DET0027: Detection of Web Protocol-Based C2 Over HTTP, HTTPS, or WebSockets]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c392a03d-b4d0-4b2c-aeaa-1b010d916922`.
