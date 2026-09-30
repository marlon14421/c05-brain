---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0343"
target_object: "T1498.001"
stix_relationship_id: "relationship--fcf5a880-eee6-45b7-8d2b-10b640b0fa62"
---
# Relationship 1647: DET0343 — detects → T1498.001

**Source object:** [[01 ATT&CK/DET0343 - Direct Network Flood Detection across IaaS, Linux, Windows, and macOS|DET0343: Direct Network Flood Detection across IaaS, Linux, Windows, and macOS]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1498.001 - Direct Network Flood|T1498.001: Direct Network Flood]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fcf5a880-eee6-45b7-8d2b-10b640b0fa62`.
