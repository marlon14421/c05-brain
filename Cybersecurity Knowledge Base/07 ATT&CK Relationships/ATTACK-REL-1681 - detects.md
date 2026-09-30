---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0287"
target_object: "T1203"
stix_relationship_id: "relationship--f094c21c-9872-4e82-88c1-c759979c4f10"
---
# Relationship 1681: DET0287 — detects → T1203

**Source object:** [[01 ATT&CK/DET0287 - Exploitation for Client Execution – cross-platform behavior chain (browser-Office-3rd|DET0287: Exploitation for Client Execution – cross-platform behavior chain (browser/Office/3rd-party apps)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1203 - Exploitation for Client Execution|T1203: Exploitation for Client Execution]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f094c21c-9872-4e82-88c1-c759979c4f10`.
